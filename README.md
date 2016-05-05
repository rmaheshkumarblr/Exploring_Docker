# Exploring Docker
Exploring how Docker works and trying a build a basic application

Trying build a basic full stack using docker.

Installed Docket-Toolbox:

`https://www.docker.com/products/docker-toolbox`

Get MongoDB Docker Image:

`docker pull mongo`

Start MongoDB:
NOTE: 192.168.99.100 is the IP at which docker is running at. The first 27017 is the port at which MongoDB would run on the Docker Image. The second 27017 is the port in MAC/Computer where we can access the port 27017 of the Docker Image.
 
`docker run -p 192.168.99.100:27017:27017 -d mongo`



