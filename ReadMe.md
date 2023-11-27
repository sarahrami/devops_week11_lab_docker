
# Run following command on terminal

docker build --tag=101376641_hello_docker .
docker build -t 101376641_hello_docker .

docker image ls

docker run -p 4000:80 101376641_hello_docker

docker run --name=lab11DevOps -p 4000:80 101376641_hello_docker

docker container stop CONTAINER_ID

docker container ls