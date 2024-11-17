# NGINX with PHP 8.2 Docker Setup

This repository provides a Docker configuration for setting up a PHP 8.2 environment with NGINX on Ubuntu 22.04. It is ideal for deploying PHP-based applications like Laravel or phpMyAdmin.

---

## Features

- **Base Image:** `ubuntu:22.04`
- **Web Server:** NGINX
- **PHP Version:** 8.2
- **Included PHP Extensions:**
  - `bcmath`, `xml`, `mysql`, `zip`, `intl`, `ldap`, `gd`, `cli`, `bz2`, `curl`, `mbstring`, `pgsql`, `opcache`, `soap`, `cgi`
- **Customizable:** Supports custom NGINX and PHP configurations.

---

## Prerequisites

Before you begin, ensure you have:

- [Docker](https://www.docker.com/) installed.
- A PHP application you want to deploy (e.g., Laravel or phpMyAdmin).

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ravikantchauhan/phpMyAdmin-docker.git
cd phpMyAdmin-docker
