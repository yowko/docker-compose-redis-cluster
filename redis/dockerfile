FROM redis:6.0.3
MAINTAINER Yowko Tsai <yowko@yowko.com>
COPY rediscluster.conf /etc/redis/rediscluster.conf
ENTRYPOINT redis-server /etc/redis/rediscluster.conf