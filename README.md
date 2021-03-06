# RICK AND MORTY APP

Rick and morty app developed as hobby project.


[Live Demo](https://rick-and-morty-app.herokuapp.com/)

![Heroku](https://heroku-badge.herokuapp.com/?app=rick-and-morty-app)


## Usage

Clone repository with one of the following ways and start coding.

with HTTPS:

```shell
git clone https://github.com/furkanyilmazx/rick-and-morty-app.git
```

with SSH:

```shell
git clone git@github.com:furkanyilmazx/rick-and-morty-app.git
```

## Install
```shell
npm i
```
## Development
```shell
npm start
```

## Build
```shell
npm run build
```

## Deployment

### Build as Docker image
```shell
docker build --rm -t rick-and-morty-app .
```
### Run as a Docker container
```shell
docker run -di --name rick-and-morty-app -p 8888:80 rick-and-morty-app
```
### Install from docker hub
```shell
docker pull furkanyilmaz/rick-and-morty-app:latest
docker run -di --name rick-and-morty-app -p 8888:80 furkanyilmaz/rick-and-morty-app:latest
```
