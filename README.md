# myappstore
Module to create product content type.

This module requires latest drupal 9 must be installed wia composer.

The package ``chillerlan/php-qrcode`` is required, this dependency has to be met by running 

``composer require "chillerlan/php-qrcode": "^4.0"``


It is assumed that the ``Olivero`` theme is the default theme of the drupal installation.
Or It can be done by ``drush config-set -y system.theme default olivero``

Install module by running 

``drush en product``

Now visit the product page (node/1)