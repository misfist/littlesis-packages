=== LittleSis Blog Project ===
Contributors: misfist
Requires at least: 4.7
Tested up to: 4.7.3
License: GPLv3

WordPress packages for blog.littlesis.org

== Description ==
Package configuration for WordPress plugins and themes used on blog.littlesis.org.

== Installation ==
The `composer.json` file contains the packages used by the site.

Run `composer install` (or `composer install --no-dev`) within the package directory in order to install for the first time.
Run `composer update` (or `composer update --no-dev`)  within the package directory in order to update the project.

Important: When installing or updating on a production environment, use the `--no-dev` flag so that packages used for development are not included.

Project structure

```
webroot
 \\_ core-packages <-- contains composer.json - installs packages into `wordpress` directory
 \\_ wordpress <-- contains wordpress core and packages
```

== Changelog ==

0.1.9 - April 7, 2017
* Added Google Analytics Dashboard for WP
* Added MailChimp for WordPress

0.1.8 - April 5, 2017
* Updated theme to v0.1.8

0.1.7 - March 31, 2017
* Updated theme to v0.1.7

0.1.6
* Updated theme to v0.1.6

0.1.5
* Updated theme to v0.1.5

0.1.4.1
* Updated theme to v0.1.4.1

0.1.4
* Updated theme to v0.1.4
* Updated core plugin to v0.1.3

0.1.3
* Updated theme to v0.1.3

0.1.2
* Updated theme to v0.1.2

0.1.1
* Updated theme to v0.1.1

0.1.0
* Updated theme to v0.1.0

0.0.10
* Updated theme to v0.0.10
* Updated core plugin to v0.1.2
* Added shortcode-ui plugin

0.0.9
* Updated theme to v0.0.9

0.0.8
* Updated theme to v0.0.8
* Added Core Functionality plugin

0.0.7 - Updated theme to v0.0.7

0.0.6 - Updated theme to v0.0.6

0.0.5 - Updated theme to v0.0.5

0.0.2 - Updated theme to 0.0.2

0.0.1 - Initial
