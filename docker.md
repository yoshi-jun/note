# Docker

## How to install by brew

```shell
$ brew install --cask docker
```

## Settings

Open the docker app from Application directory and start docker.
The setting of docker is automaticaly finish.

## Test run

```shell
$ brew docker hello-wrold
```

## Pull images

```shell
$ docker pull ubuntu:latest
```

## Run container

```shell
$ docker run -it --name [name] [container name]
```

## Check docker process

```shell
$ docker ps
```

Show the stopping container
```
$ docker ps -a
```

