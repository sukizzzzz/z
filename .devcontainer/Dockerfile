FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the Vue.js
RUN apt-get update && \
npm install -g @vue/cli
#Install flask 
RUN apt-get update && \
    apt-get install -y python3-pip && \
    pip3 install Flask