# docker-laravel
Reverse Proxy Nginx: Docker Laravel Multi-stage Build

# run project

1. `docker-compose up --build -d`


# generate images

1. `docker build -t <your-tag-name> <diretory> -f <name-docker-file>`

1. Example: `docker build -t tom/laravel:prod laravel -f laravel/Dockerfile.prod`

# list image

1. `docker images | grep <name-image>`

# remove image

1. `docker rmi <your-tag-name>`
