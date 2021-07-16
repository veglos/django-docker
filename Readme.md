# README

Basic template for Django project with optional Docker support for developement.
A specific step-by-step guide can be found [here](https://veglos.github.io/posts/setup-django-and-docker/).

## Deploy with docker

``` shell
docker-compose up
```
Configuration: **.docker.env**

## Deploy without docker

``` shell
python manage.py runserver
```

Configuration: **.local.env**
