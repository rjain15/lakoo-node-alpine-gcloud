# Node Alpine Gcloud- Docker Image

Simple base image containing nodejs, git and gcloud sdk for ci usage

Base on https://hub.docker.com/_/node/ , image `node:9-alpine`
`docker build -t rjain15/node-alpine-gcloud-yarn .`
`docker push rjain15/node-alpine-gcloud-yarn:latest`

## Components included
* node
* curl
* git
* gcloud
* gzip
* kubectl
* yarn
* docker
