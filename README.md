# webdis
Run webdis server in docker container.

Includes a redis-server running in this container.

Run with env vars:
REDIS_SERVER_IP
REDIS_SERVER_PORT

To test with the redis-server running inside the container, you would run this container with the following env vars:
REDIS_SERVER_IP=127.0.0.1
REDIS_SERVER_PORT=6379
