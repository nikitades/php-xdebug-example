#Taking the core image as base
FROM php:8.2-fpm AS base

#Install and enable xdebug extension
RUN pecl install xdebug
RUN docker-php-ext-enable xdebug

#Tag the image for the future conveniency
FROM base AS runner