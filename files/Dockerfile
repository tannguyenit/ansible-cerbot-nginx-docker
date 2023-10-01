# Use the official PHP 8.0 FPM base image
FROM php:8.0.5-fpm-alpine

# Set working directory
WORKDIR /var/www/html

# Copy a PHP file into the container

RUN echo '<?php echo "Hello, PHP!"; ?>' > /var/www/html/index.php

# Expose port 9000
EXPOSE 9000
