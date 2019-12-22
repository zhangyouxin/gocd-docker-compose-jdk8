# Docker compose file to deploy 

- GoCD server and GoCD agent with openjdk8

## Requirements
* Docker
* Docker compose

## Usage

1. Clone the repo
2. From inside the repo run `docker-compose up -d` to run in daemon mode
3. Wait for a few minutes
4. Access the GoCD server at `http://<hostname>:8153`
5. To stop the stack use `docker-compose down`  