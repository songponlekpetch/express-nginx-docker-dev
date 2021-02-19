# express-nginx-docker-dev
![Run express + nginx reverproxy + docker on development environment](image.png?raw=true)

## Install
Install [docker desktop](https://www.docker.com/get-started)

Install [docker-compose](https://docs.docker.com/compose/install/)

## Add host on /etc/hosts
Open hosts file
> vim /etc/hosts

Add url mapping with nginx
> 127.0.0.0 express.com

## Run time!!!
Run docker-compose
> docker-compose up -d

Remove docker-compose and remove existing images
> docker-compose down --rmi all


## Automatically update when you edit express on local
Let you try change express and refresh page
