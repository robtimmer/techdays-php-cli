# TechDays PHP CLI
This repository contains a Docker image with the requirements for the TechDays session:
- PHP CLI
- Composer
- bash (entrypoint)
- VIM

You can run this image, for example, with the following command:
```shell
docker run --rm -it -v $(pwd):/opt/techdays/php-cli robtimmer/techdays-php-cli:alpine
```
