## Summary

This is a template for using [Static Web Server](https://static-web-server.net/) with Docker.

## Setup

Use this template, or optionally, just copy the `docker-compose.yml` file into your existing project directory.

Configure `docker-compose.yml` as required.

Current defaults are;
* Put all files that you want to serve in `public`
* No `config.toml` (use defaults)

To run the server, execute the following command.
[Static Web Server](https://static-web-server.net/) has a lot of features that can be [configured with `config.toml`](https://static-web-server.net/configuration/config-file/).

```sh
docker compose up
```

You can also install the web server binary instead of using Docker.
