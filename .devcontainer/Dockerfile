FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# Install tools dasar VPS
RUN apt-get update && apt-get install -y \
    curl \
    wget \
    git \
    sudo \
    htop \
    net-tools \
    && rm -rf /var/lib/apt/lists/*
    
