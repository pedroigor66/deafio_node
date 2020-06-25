# desafio_node

##Node JS challenge from Rocketseat.

##Application Routes:

- POST/repositories: The route must receive title, url and techs inside its requisition body. The URL must be the link to this GitHub's repository. 
When registering a new project, it must be stored inside an object in the follow format: { id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...',
techs: ["Node.js", "..."], likes: 0 }; Make sure that the ID is a UUID and to always start likes with a 0 value. 
- GET /repositories: Route that lists all the repositories.
- PUT /repositories/:id: The route must alter only the title, url and techs of the repository that have the same id that is present in the route's parameters. 
- DELETE /repositories/:id: The route must delete the repositoru with the id that is present in the route's parameter. 
- POST /repositories/:id/like: The route must increase the number of likes of the repository that is specified in the route's parameter. 
Every time the route is called, the number of likes must be increased by one. 

##Testing if everything is working fine

To fully test all the applications routes, install all the required dependencies and run the command: **yarn test**. 
