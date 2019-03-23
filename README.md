# getting started phpunit

> using phpunit example to create a test

> from: https://phpunit.de/getting-started/phpunit-8.html

## run with docker 🐳
 
 ### view version
 docker run --rm -v ~/code/getting-started-phpunit/:/home/app -w /home/app php:7-cli ./vendor/bin/phpunit --version

 ### run test with composer 🙌
 docker run --rm -v ~/code/getting-started-phpunit/:/home/app -w /home/app php:7-cli ./vendor/bin/phpunit --bootstrap vendor/autoload.php tests/EmailTest

 ### TestDox 😊😺
 docker run --rm -v ~/code/getting-started-phpunit/:/home/app -w /home/app php:7-cli ./vendor/bin/phpunit --bootstrap vendor/autoload.php  --testdox tests

## how to (in portuguese)

[![video making repo](https://img.youtube.com/vi/xffqPdQHrTY/0.jpg)](https://www.youtube.com/watch?v=xffqPdQHrTY)

