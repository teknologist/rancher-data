FROM busybox:latest
MAINTAINER Eric Taïeb Walch <teknologist@gmail.com>
RUN mkdir -p /var/lib/cattle /var/lib/mysql /var/log/mysql
RUN chmod 777 -R /var/lib/cattle /var/lib/mysql /var/log/mysql
VOLUME /var/lib/cattle
VOLUME /var/lib/mysql
VOLUME /var/log/mysql
