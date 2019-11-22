To run project:

0. install docker

1. docker pull jupyter/datascience-notebook:latest

2. docker run --rm -it -p 8888:8888 -v $(pwd):/home/jovyan/work/ jupyter/datascience-notebook:latest 