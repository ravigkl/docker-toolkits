# docker-toolkits - It will provide a ready to use guide for docker, docker-compose and docker scout
# What is Docker - It is client-server technology, where docker is client and dockerd is server.
# What is docker-compose - It is collection of docker commands to manage multi-container applications in a file. Docker Compose v1 has stopped updates from July 2023. So now Docker Compose v2 should be used.
# What is Docker Scout - It is a vulnerability tracking and recommendation for the fixes of the vulnerabilities. It can be integrated with Docker Hub, ECR, ACR, Sonarquebe, CI/CD
---
## Docker Compose
It is a tool for definining and running multi-container Docker applications. It used YAML file to configure application's services. <br/>
The key features of Docker Compose are:
- multiple isolated environments on a single host
- Preserve volume data when created and by default does not destroy on application stop/remove
- Only re-create containers that have changed
- Support variables and moving a composition between environments

## Docker Compose Key Features
It is a 3 steps process
- Create Dockerfile at the root of the project
- Create compose.yml file for the services
- Run the `docker compose up` from the root of the project to run all the services
### Tear down all services
`docker compose down`
