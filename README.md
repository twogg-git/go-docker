![deploying-docker-hub](docker-hub.png)
### Docker Hub

#### Overview 
Docker Hub is a cloud-based registry service which allows you to link to code repositories, build your images and test them, stores manually pushed images, and links to Docker Cloud so you can deploy images to your hosts. It provides a centralized resource for container image discovery, distribution and change management, user and team collaboration, and workflow automation throughout the development pipeline.

#### Docker recipe 

This `Dockerfile` is linked with an automated build on Docker Hub repository. When this repository is updated, it will automatically trigger a rebuild of the image.

Docker Hub link: [Docker-Hub-Recipe](https://hub.docker.com/r/twogghub/go-docker/)

#### Out Yet! app (Golang)

Outyet is a web server that announces whether or not a particular Go version
has been tagged.

```sh
docker run -p 6060:8080 -d twogghub/go-docker 
```

```sh
localhost:6060 
```






