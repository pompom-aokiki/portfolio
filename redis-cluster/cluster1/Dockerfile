FROM redis:latest
COPY redis.conf /usr/local/etc/redis/redis.conf
COPY nodes.conf nodes.conf
CMD ["redis-server","/usr/local/etc/redis/redis.conf"]