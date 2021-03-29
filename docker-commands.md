# Docker Cheat Sheet
>Summary of basic docker commands

### docker run [-d] < image >
> -d is detach mode it will not use console and will run in background.
### docker ps
> lists all current containers state

### docker stop < [ id | name] >
### docker rm < container-name|id  >
### docker images
> lists all existing images.
### docker rmi < images-name >

### docker pull
> gets image only, will not run it.

### docker exec < container_id > < command-to-execute >
> executes a command on a container.

