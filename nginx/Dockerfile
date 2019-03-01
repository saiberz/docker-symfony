FROM nginx:1.15
RUN apt update && apt install -y iputils-ping
COPY nginx.default.conf /etc/nginx/conf.d/default.conf

