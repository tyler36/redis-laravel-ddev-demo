# REDIS Laravel DDEV demo <!-- omit in toc -->

- [Intro](#intro)
  - [Requirements](#requirements)
- [Setup](#setup)

## Intro

This repo demonstrates setup steps for a [redis](https://redis.com/) server for [Laravel](https://laravel.com/) via [DDEV](https://github.com/drud/ddev).

### Requirements

- PHP >= 8.0
- [Composer](https://getcomposer.org/doc/00-intro.md) >= 2.2.6
- [DDEV](https://github.com/drud/ddev) >= 1.18

## Setup

- Clone repo
- Install dependencies

```shell
composer install
```

- Setup Laravel `.env`

```shell
cp .env.example .env
```

- Generate Laravel key

```shell
$ php artisan key:generate
Application key set successfully.
```
