#### SAMPLE SPRING MICROSERVICES USING DOCKER & KUBERNETES

Cloning Submodules

git clone /url/to/repo/with/submodules

git submodule init

git submodule update

Packaging with Maven and Docker and Deploy to Docker Hub
from each submodule run the following to package and deploy to DockerHub:
 
 mvn clean install
 
 mvn dockerfile:push
 
 Deploy with Docker Compose
 
 docker-compose up -d
 
 Deploy with Kubernetes
 TODO
 
 