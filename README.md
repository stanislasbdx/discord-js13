# 🤖 — Discord.js 14 Pterodactyl Bot Hosting Egg and Docker image

This is an egg dedicated to NodeJS bot hosting (discord.js v14 & nodejs v18.12) on pterodactyl panel.

Docker image: <https://hub.docker.com/r/5140/discord-egg>

Docker image used: <https://hub.docker.com/_/node> (18.12-slim)

A problem ? A suggestion ? DM me on discord (stan1712) !

## 🏗️・Installation

To install this egg :

1. Go into Admin panel
2. Go to "Nests"
3. Click "Import Egg"
4. Choose the .json file named "egg-discordjs-14"
5. And import !

## 🌌・Usage

To use it, just create a server with this egg in the "Nest Configuration" section.

## 🤝・Contributing

### Building a Docker image

You can build the docker image with the LTS Node version, or a specific version.

```bash
podman build .

# To build in specific Node version
podman build --build-arg NODE_VERSION=18 .
```
