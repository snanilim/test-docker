FROM php:7-fpm

RUN apt-get update \
 && apt-get install -y git zlib1g-dev \
 && docker-php-ext-install pdo pdo_mysql 

WORKDIR /var/www