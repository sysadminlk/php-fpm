## Introduction
This is a Dockerfile to build a debian based container image running nginx and php-fpm 8.3.x & Composer.

## Building from source
To build from source you need to clone the git repo and run docker build:
```
$ git clone https://github.com/sysadminlk/php-fpm.git
$ cd nginx-php-fpm
```

followed by
```
$ docker build -t nginx-php-fpm:php83 . # PHP 8.23.x
```


## Pulling from Docker Hub
```
$ docker pull sysadminlk/nginx-php-fpm:php83
```

## Running
To run the container:
```
$ sudo docker run -d sysadminlk/nginx-php-fpm:php83
```

Default web root:
```
/usr/share/nginx/html
```
