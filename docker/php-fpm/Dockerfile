FROM thecodingmachine/php:7.2-v2-fpm-node10

#USER root

# Fix debconf warnings upon build
#ARG DEBIAN_FRONTEND=noninteractive

#RUN apt-get update \
#    && cd /usr/local/lib/thecodingmachine-php/extensions/current/pgsql && ./install.sh \
#    && cd /usr/local/lib/thecodingmachine-php/extensions/current/bcmath && ./install.sh \
#    && cd /usr/local/lib/thecodingmachine-php/extensions/current/gd && ./install.sh \
#    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*

#USER docker