# Hubzilla on Docker

This setup has been adopted from earlier work by <https://github.com/Grawl/hubzilla-docker/>. The current setup updates php to 8.2 and traefik integration has been removed to simplify the process.

# Installation

The follwoing files need to be updated:
* src/container_apache.conf
* hub.conf
* ssmtp.conf
* docker-compose.yml

after the relevant variables have been modified, run:
    docker compose up -d --build

# Status
There is a lot of minor improvements that can be done to streamline the process and make it easy for deployment. Collaborations are welcome.
