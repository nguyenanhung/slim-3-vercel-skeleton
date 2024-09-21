[![Latest Stable Version](https://img.shields.io/packagist/v/nguyenanhung/slim-3-vercel-skeleton.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/slim-3-vercel-skeleton)
[![Total Downloads](https://img.shields.io/packagist/dt/nguyenanhung/slim-3-vercel-skeleton.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/slim-3-vercel-skeleton)
[![Daily Downloads](https://img.shields.io/packagist/dd/nguyenanhung/slim-3-vercel-skeleton.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/slim-3-vercel-skeleton)
[![Monthly Downloads](https://img.shields.io/packagist/dm/nguyenanhung/slim-3-vercel-skeleton.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/slim-3-vercel-skeleton)
[![License](https://img.shields.io/packagist/l/nguyenanhung/slim-3-vercel-skeleton.svg?style=flat-square)](https://packagist.org/packages/nguyenanhung/slim-3-vercel-skeleton)
[![PHP Version Require](https://img.shields.io/packagist/dependency-v/nguyenanhung/slim-3-vercel-skeleton/php)](https://packagist.org/packages/nguyenanhung/slim-3-vercel-skeleton)

# Slim Framework 3 Skeleton Application

Use this skeleton application to quickly setup and start working on a new Slim Framework 3 application. This application
uses the latest Slim 3 with the **PHP-View** template renderer, **Slim-PDO** is Database Handle, **symfony/console** is
Console
Handle. It also uses the **Monolog** logger.

This skeleton application was built for Composer. This makes setting up a new Slim Framework application quick and easy.

## Install the Application

Run this command from the directory in which you want to install your new Slim Framework application.

```shell
composer create-project nguyenanhung/slim-3-vercel-skeleton [my-app-name]
```

or

```shell
php composer.phar create-project nguyenanhung/slim-3-vercel-skeleton [my-app-name]
```

Replace `[my-app-name]` with the desired directory name for your new application. You'll want to:

* Point your virtual host document root to your new application's `public/` directory.
* Ensure `logs/` is web writeable.

To run the application in development, you can run these commands

```shell
cd [my-app-name]
php composer.phar start
```

Run this command in the application directory to run the test suite

```shell
php composer.phar test
```

or

```shell
./vendor/bin/phpunit
```

That's it! Now go build something cool.

## Contact

If any question & request, please contact following information

| Name        | Email                | GitHub        | Facebook      |
|-------------|----------------------|---------------|---------------|
| Hung Nguyen | dev@nguyenanhung.com | @nguyenanhung | @nguyenanhung |

From Hanoi with Love <3

