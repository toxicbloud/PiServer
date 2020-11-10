
FROM php:fpm-alpine
RUN apk update && apk add --no-cache
RUN docker-php-ext-install mysqli && \
    docker-php-ext-install pdo_mysql
