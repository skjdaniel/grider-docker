This repo contains code for a project from Stephen Grider's Udemy course [Docker and Kubernetes: The Complete Guide](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/).

The aim is to build a web app which calculates terms in the Fibonacci sequence, and to deploy the app using Elastic Beanstalk. The architecture of the app (for development and production) is shown below (the images are screenshots from the course). The architecture is over-complicated by design; the point here is to learn how to use Docker to build and deploy an app with multiple containers. (Indeed, the code in the client, server, worker, and nginx folders was downloaded from the course resources.)

Travis CI is used for CI/CD (not shown below).

![](/images/multi-docker-dev.png)

![](/images/multi-docker-prod.png)
