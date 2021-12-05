# docker-php8.1 + symfony 5.4 +Mysql 8.0

This repository contains the basic configuration for a complete local environment for Symfony projects

### Content:
- NGINX 1.21 container to handle HTTP requests
- PHP 8.1 container to host your Symfony application
- MySQL 8.0 container to store databases

(feel free to update any version in `Dockerfiles` and ports in `docker-compose.yml`)

### Installation:
- Run `make build` to create all containers 
- Run `make start` to spin up containers
- Enter the PHP container with `make ssh-be`
- Navigate to `localhost:1000` so you can see the Symfony welcome page :)

Happy coding!
