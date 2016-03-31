FROM drupaldocker/php:5.6-fpm

RUN apt-get update &&  pecl install redis  \
    && docker-php-ext-enable redis \
    && rm -rf /var/lib/apt/lists/*
