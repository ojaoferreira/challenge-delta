FROM nginx:1.19.1-alpine

RUN ln -sf /dev/stdout /var/log/nginx/access.log \
    && ln -sf /dev/stderr /var/log/nginx/error.log

ADD default.conf.template /etc/nginx/templates/default.conf.template