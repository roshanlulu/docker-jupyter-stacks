
##  Opinionated stacks of ready-to-run Jupyter applications in Docker.


- The`Dockerfile` is required for setting up the environment

- The `docker-compose.yml` file defines the services

- Build image locally ( This will create a local image by pulling base image and other dependencies defined in `Dockerfile` )
`Note: This will take a while since the dependant image from docker hub has to be pulled(downloaded and extracted) and build locally`
```
docker-compose build jupyter
```
- Command to run jupyter service to open a jupyter notebook running on docker
```
docker-compose up jupyter
```

### Credits: [Jupyter @Github](https://github.com/jupyter/docker-stacks/tree/master/all-spark-notebook)