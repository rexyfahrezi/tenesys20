FROM php:7.3-apache

RUN a2enmod rewrite

COPY . /var/www/html/

RUN chown -R www-data:www-data /var/www/html

CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]

