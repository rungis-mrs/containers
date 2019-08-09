FROM php:7-fpm

RUN apt-get update && apt-get install -y \
    libmagickwand-dev --no-install-recommends \
        && pecl install imagick \
    	&& docker-php-ext-enable imagick


