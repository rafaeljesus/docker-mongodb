# Docker Mongodb

Dockerfile to build a MongoDb container image

[![Docker Image Size](https://img.shields.io/imagelayers/image-size/rafaeljesus/docker-mongodb/latest.svg)](https://hub.docker.com/r/rafaeljesus/docker-mongodb/)
[![Docker Image Pulls](https://img.shields.io/docker/pulls/rafaeljesus/event-track.svg)](https://hub.docker.com/r/rafaeljesus/docker-mongodb/)

## Usage
```bash
$ docker-machine start default
$ eval $(docker-machine env default)
$ docker run --name mongo -d rafaeljesus/docker-mongodb --smallfiles
```

## Contributing
- Fork it
- Create your feature branch (`git checkout -b my-new-feature`)
- Commit your changes (`git commit -am 'Add some feature'`)
- Push to the branch (`git push origin my-new-feature`)
- Create new Pull Request

### Maintaners

* [Rafael Jesus](https://github.com/rafaeljesus)
