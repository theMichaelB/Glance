# Glance

## Overview

**Glance** is a Golang-based web application created to facilitate learning and development of DevOps skills. The initial version of Glance serves as a simple dashboard that displays essential information about the host system it is running on. As the project evolves, Glance will incorporate additional microservices, databases, caching layers, and comprehensive observability features to emulate a typical enterprise environment.

## Features (MVP)

- **Host Information Dashboard**
  - Displays CPU usage, memory usage, disk usage, and network statistics.
  - Shows OS details including name, version, and uptime.
  - Lists key environment variables relevant to the host.

- **Web Interface**
  - Responsive and intuitive dashboard built with HTML, CSS, and JavaScript.
  - Accessible on desktops, tablets, and smartphones.

- **API Endpoints**
  - `GET /api/host`: Retrieves host information in JSON format.

- **DevOps Integrations**
  - **Containerization**: Dockerfile included for easy containerization.
  - **Orchestration**: Kubernetes manifests for deploying to a local cluster.
  - **CI/CD Pipeline**: Automated builds, tests, and deployments using GitHub Actions.
  - **Observability**: Basic logging and metrics collection with Prometheus and Grafana.
