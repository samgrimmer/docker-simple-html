# docker-simple-html

using docker with nginx to serve basic html

### Getting started

```
docker build image -t nginx-html .

# build docker image and tag
docker build -t nginx-html .

# check created docker image
docker image list

# run docker image and map internal container port to external port
docker run -d -p 8080:80 nginx-html

# check running docker process
docker ps
```