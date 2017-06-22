# Docker file to create an environment for samples building.

FROM ubuntu

RUN apt-get update && apt-get -y install    \
        default-jdk                         \
        libgit2-dev                         \
        libgtk-3-dev                        \
        freeglut3-dev                       \
        libsdl1.2-dev                       \
    && rm -rf /var/lib/apt/lists/*
