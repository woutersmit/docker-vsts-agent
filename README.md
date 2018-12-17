# vsts-agent

The `standard + docker` images are quite large +_12+GB.

This is an image based on vsts-agent:ubuntu-16.04-tfs-2018-u3-docker-17.12.0-ce

With additional sdk/tools:
- basic command-line utilities
- docker / docker-compose
- azure cli
- ms sql server client tools
- dotnet core sdk
- azcopy
- powershell core
- rancher cli
- vsts-agent

## Build

`docker build . -t woutersmit/docker-vsts-agent:0.1`
