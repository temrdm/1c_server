# 1C Server

## Prepare

    1C_VER=8.3.6-2299 # For example

## Download dependency

Download platform deb package from [users.v8.1c.ru](https://users.v8.1c.ru/distribution/project/Platform83) and extract it to ```./${1C_VER}/dist``` path.

## Build

    docker build -t {repo_name}/1c_server:${1C_VER} ./${1C_VER}
    docker build -t {repo_name}/1c_server ./${1C_VER}

## Push
    
    docker push {repo_name}/1c_server:${1C_VER}
    docker push {repo_name}/1c_server

## Pull built containers

Built containers [here] (https://hub.docker.com/r/temrdm/1c_server/)
