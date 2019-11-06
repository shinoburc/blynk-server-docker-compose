# blynk-server-docker-compose

## Setup

```sh
$ git clone https://github.com/shinoburc/blynk-server-docker-compose.git
$ cd blynk-server-docker-compose
$ docker-compose up -d
```
## Setup for raspberrypi

```sh
$ git clone https://github.com/shinoburc/blynk-server-docker-compose.git
$ cd blynk-server-docker-compose
$ vi docker-compose.yml
```
```yaml
    services:
    blynk:
      #image: mpherg/blynk-server:latest
      build:
        context: blynk
```
```sh
$ docker-compose up -d
```

## Reference

- [GitHub - blynkkk/blynk-server](https://github.com/blynkkk/blynk-server)
- [DockerHub - mpherg/blynk-server](https://hub.docker.com/r/mpherg/blynk-server/)
