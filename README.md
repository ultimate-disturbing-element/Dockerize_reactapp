# Getting Started with Docker + React App

## Docker Command

1)Check Available  Docker Image -> docker image ls

2)Running Container -> docker ps

3)All Container -> docker ps -a

4)Build Image -> docker build-t name_of_the_image

5)Run Container -> docker run -d --name name_of_container name_of_image

6)Run Container with Port -> docker run -d -p local_machine_port:container_port -name name_of_container name_of_image

7)Run Container With Volume(Bind Mount Read Only) -> docker run -v path_of_local_dir:container_dir:ro -d -p local_machine_port:container_port -name name_of_container name_of_image

8)Adding Environmental Variable -> docker run --env-file ./.env -v path_of_local_dir:container_dir:ro -d -p local_machine_port:container_port -name name_of_container name_of_image
