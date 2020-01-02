FROM distracing/zipkin-nginx:1.15

COPY libdd_opentracing_plugin.so /usr/local/lib

COPY nginx.conf /etc/nginx/nginx.conf

COPY dd-config.json /etc
