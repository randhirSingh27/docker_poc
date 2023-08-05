Docker Components:

Docker Engine: The core component responsible for running and managing containers on a host system.
Docker Images: Immutable templates that contain the application code and its dependencies.
Docker Containers: Instances of Docker images that run as isolated processes on the host system.
Docker Registry: A repository for storing and sharing Docker images (Docker Hub is a popular public registry).


Dockerfile:
A text file that contains instructions to build a Docker image. It defines the base image, copies files into the image, installs dependencies, sets environment variables, and more.

Docker Commands:

docker build: Builds a Docker image from a Dockerfile.
docker run: Creates and starts a container from a Docker image.
docker ps: Lists running containers.
docker images: Lists available Docker images.
docker stop: Stops one or more running containers.
docker rm: Removes one or more containers.
docker rmi: Removes one or more images.

Docker Compose:
A tool for defining and managing multi-container Docker applications. Compose uses a YAML file to configure the services, networks, and volumes needed for the application.

Docker Volumes:
Volumes provide persistent storage for containers. They enable data to be shared between the host and containers or between multiple containers.

Docker Swarm:
Docker Swarm is a native clustering and orchestration tool within Docker, allowing you to create and manage a cluster of Docker nodes.
