FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update && apt-get install -y xz-utils

#Install Vue CLI globally
RUN npm install -g @vue/cli

#Install Flask using pip
RUN pip3 install Flask