## Dockerized Laravel Application

A simple dockerize laravel application

Create a fresh laravel application

```
docker run --rm -v %cd%:/app composer create-project laravel/laravel my-dockerize-app && docker rmi composer
```
