Quiz demo: Mouf + Wordpress
===========================

This repository contains a PHP Quiz demo application, running on Drupal.

You can access the website by browsing http://demoquiz-drupal.mouf-php.com/quiz

It is part of a wider demo, showcasing how to deploy on **same code** in many different environments.

Installation
------------

- Clone the repository
- Run `composer install`
- Browse to the website root directory and run Drupal install
- Browse to http://[your-website]/[path-to-drupal]/vendor/mouf/mouf and run Mouf install process
- Configure the `RewriteBase` setting in the `.htaccess` file (if needed)
- Connect to the Drupal admin, and enable the Druplash module
- Enable the *Clean URLs* settings: Administration > Configuration > Clean URLs
- Purge all Drupal caches: Administration > Configuration > Performance > Clear all caches
- You are done!
- Now, simply browse to: http://[your-website]/[path-to-drupal]/quiz
