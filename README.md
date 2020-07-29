# DevOps Girls Docker 101

## What This Is

This is a workshop which introduces basic Docker concepts - how to use it, why it's important, and where to get more information afterwards. This workshop is designed to be self-running, and contains practical and conceptual information inside the repository.

This workshop aims to for the comprehension and application of Docker knowledge.

## Prerequisites (Docker)

Before beginning this workshop, you must:

 - Install Docker ( [Instructions for Windows](https://docs.docker.com/v17.09/docker-for-windows/install/) / [Instructions for Macs](https://docs.docker.com/docker-for-mac/install/) )

 - Signup for an account in [Docker Hub](https://hub.docker.com/)

 - After signing up for an account, make sure you can login by running the following in your command line:

```
docker login
```

## Prerequisites (Kubernetes)

#### The Easy Way (Using Labs)

If you don't want to install Kubernetes components, you can use the online instances at: [Play With Kubernetes.](https://labs.play-with-k8s.com/)

Instructions are over here:


#### The Not-so-easy Way (Using Minikube)

If you want to install a single-node Kubernetes cluster on your machine to play with, you can install with [Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/).

Instructions are over here:


## The Workshop


#### Docker

The Docker workshop has three components:

 - [Part 0: Docker Concepts.](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/0-Concepts.md) In this part, we'll review *what Docker is* and why it is important.

 - [Part 1: Docker Basics.](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/1-Basics.md) In this part of the workshop, we'll go through basic commands to run containers and pull images. 

 - [Part 2: Creating Docker Images.](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/2-Images.md) We'll break down how to create your own Docker images.

 - [Part 3: Docker Tagging.](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/3-Tags-and-Push.md) We'll take a look at what Docker tags are, and how to publish your images.


#### Kubernetes

 - [Part 4: Kubernetes Concepts.](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/4-K8S-Concepts.md)

 - [Part 5: Kubernetes Basics, and the Command Line](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/5-Kubernetes-Basics.md)

 - [Part 6: Pods and Services](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/6-Pods-and-Services.md)

 - [Part 7: Deployments and Labels](https://github.com/DevOps-Girls/from-docker-to-kubernetes/blob/master/7-Deployments-and-Labels.md)
