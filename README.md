Reverser# Nginx Reverse Proxy Setup with Docker Compose

## Overview
This project sets up a reverse proxy using Nginx and Docker Compose. It hosts two simple Nginx websites (`site1` and `site2`) behind a reverse proxy.

## Project Structure
```
├── docker-compose.yml
├── reverse-proxy/
│ └── default.conf
├── site1/
│ ├── index.html
│ └── default.conf
└── site2/
├── index.html
└── default.conf
```