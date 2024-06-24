```
# build image from Dockerfile
docker build -t yongkin45/ubuntu-2204 .

# run the docker container interactively, also giving it a name
docker run -it --name my_container_name yongkin45/ubuntu-2204 /bin/bash

# push the built image
docker push yongkin45/ubuntu-2204
```
