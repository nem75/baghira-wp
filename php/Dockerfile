FROM php:7.1-fpm-alpine

RUN docker-php-ext-install opcache mysqli

COPY www.conf zz-docker.conf /usr/local/etc/php-fpm.d/
COPY php.ini /usr/local/etc/php/

WORKDIR /app
