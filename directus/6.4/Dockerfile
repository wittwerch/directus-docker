FROM getdirectus/directus-base-layer:0.0.9
MAINTAINER Kristian Frolund "https://github.com/Froelund"

RUN get-directus 6.4.0-rc.1
RUN composer install -o -d /var/www/html/
RUN fix-directus-permissions
