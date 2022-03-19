# Consul Docker Compose Environment

This is an easy to setup environment for running three consul servers.

Three services are started using the base image 'consul'. The services have static IPs defined in the docker-compose file. Each server has its own config and data volumes mounted.

## Usage

Run `docker compose up`
