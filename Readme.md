# About this Repo

This repo is a static site which will contain personal pages.

## generate self signed SSL crt

    openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/nginx.key -out /etc/nginx/ssl/nginx.crt
