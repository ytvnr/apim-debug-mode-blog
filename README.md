# Troubleshoot your APIs with the Gravitee APIM Debug Mode!

This is the supporting repository for the Gravitee APIM Debug Mode blog post.

## Supporting material:

You can import those APIs to play with as in the blog post.

- [Library Backend API Definition](https://raw.githubusercontent.com/ytvnr/apim-debug-mode-blog/main/Library-Backend-1.json) is used as a backend for `Library API`
- [Library API Definition](https://raw.githubusercontent.com/ytvnr/apim-debug-mode-blog/main/Library-1.json) is the API used to demonstrate the Debug Mode feature in the blog.

## Run a local APIM with docker-compose:

You can run this command to run a local installation of APIM:

`cd /tmp && mkdir -p apim && cd apim && curl -L https://raw.githubusercontent.com/gravitee-io/gravitee-docker/master/apim/3.x/docker-compose.yml -o "docker-compose.yml" && export APIM_VERSION=3.17.1 && docker-compose down -v && docker-compose pull && docker-compose up`

### Gravitee APIM URLs:

- http://localhost:8082 - APIM Gateway

- http://localhost:8084 - APIM Management Console

- http://localhost:8085 - APIM Developer Portal

### Default credentials:

- Username: admin

- Password: admin