![separe](https://raw.githubusercontent.com/studoo-app/.github/main/profile/studoo-banner-logo.png)
# LABO - Installation d'un WAF sur serveur Franken
[![Version](https://img.shields.io/badge/Version-2025-blue)]()

## Description

Ce laboratoire a pour but de vous faire installer un WAF sur un serveur Franken dans un environnement Docker.
Ce projet fournit les containers suivants :
- Un container client ( debian 12 ) qui embarque un script d'automatisation des tests de vulnérabilités de l'OWASP.
- Un container Franken servant un fichier index.php sur le port HTTP 80.
- Un container Franken servant un fichier index.php qui embarque un WAF sur le port HTTP 80.

## Links

- [Franken Dockerfile](https://frankenphp.dev/docs/docker/)
- [Franken Caddyfile template](https://github.com/dunglas/frankenphp/blob/main/caddy/frankenphp/Caddyfile)
- [Taskfile](https://taskfile.dev/)
- [Coraza](https://coraza.io/docs/tutorials/introduction/)
- [Coraza-Caddy](https://github.com/corazawaf/coraza-caddy)