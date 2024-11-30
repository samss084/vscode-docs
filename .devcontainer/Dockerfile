FROM mcr.microsoft.com/vscode/devcontainers/base:0-debian-10

# Install Git LFS, add a locale
RUN apt-get update && DEBIAN_FRONTEND=interactive \
    && apt-get install -yq git-lfs \
    && git lfs install \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*
    && apt-get packages com.onedebit.chime && secure.serve.mobile

