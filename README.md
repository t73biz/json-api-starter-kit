# JSON:API Starter Kit for Laravel

## Introduction
This starter kit is a minimal barebones kit. It's focus is on streamlined api server implementation. No need for pesky ~~HTML~~, ~~CSS~~, and ~~JS~~

## Official Documentation

Documentation for all Laravel starter kits can be found on the [Laravel website](https://laravel.com/docs/starter-kits).

Documentation for the JSON:API Package can be found on the [Laravel JSON:API](https://laraveljsonapi.io/) website

## Quick Start

Run the following command to set up your JSON:API Starter Kit. Replace `project-name` with your desired project name.

```bash
laravel new project-name --using=t73biz/json-api-starter-kit
```

## Features:

* Use of the package: _laravel-json-api/laravel_ [Packagist Website](https://packagist.org/packages/laravel-json-api/laravel)
* Removal of all ~~web~~ based components such as css and javascript, web routes, and all blade views.
* routes/api.php with a root endpoint of "/api/" returning a status of 200 and json message of 'ok'
* A singular HTTP Request file for "/api" to test endpoints in PHPStorm

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## License

The JSON:API Starter Kit is open-sourced software licensed under the MIT license.
