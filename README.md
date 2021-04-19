[![CodeFactor](https://www.codefactor.io/repository/github/sergeevpasha/php-docker-image/badge)](https://www.codefactor.io/repository/github/sergeevpasha/php-docker-image)
[![Docker Image CI](https://github.com/sergeevpasha/php-docker-image/actions/workflows/dockerimage.yml/badge.svg)](https://github.com/sergeevpasha/php-docker-image/actions/workflows/dockerimage.yml)

# Laravel PHP docker image

Built on PHP 8.0-FPM image

PHP with most used modules for both development and production environments

Main locale: en_US.UTF-8

## PHP Modules

* bcmath       
* Core
* ctype
* curl
* date
* dom
* exif
* fileinfo
* filter
* ftp
* gd
* gettext
* hash
* iconv
* imap
* intl
* json
* libxml
* mbstring
* mysqli
* mysqlnd
* openssl
* pcntl
* pcre
* PDO
* pdo_mysql
* pdo_pgsql
* pdo_sqlite
* Phar
* posix
* readline
* redis
* Reflection
* session
* SimpleXML
* soap
* sodium
* SPL
* sqlite3
* standard
* tokenizer
* xml
* xmlreader
* xmlwriter
* zip
* zlib

# Additional Software
* Cron

Example configuration for docker-compose.yml
```
app:
    image: sergeevpasha/php:latest
    tty: true
    volumes:
        - ./:/var/www
    networks:
        - some-network
```
