[![Docker Pulls](https://img.shields.io/docker/pulls/zaherg/php72-swoole.svg)](https://hub.docker.com/r/zaherg/php72-swoole/) [![](https://images.microbadger.com/badges/image/zaherg/php72-swoole.svg)](https://microbadger.com/images/zaherg/php72-swoole "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/zaherg/php72-swoole.svg)](https://microbadger.com/images/zaherg/php72-swoole "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/commit/zaherg/php72-swoole.svg)](https://microbadger.com/images/zaherg/php72-swoole "Get your own commit badge on microbadger.com")  [![](https://img.shields.io/github/last-commit/linuxjuggler/php72-swoole.svg)](https://github.com/linuxjuggler/php72-swoole)


_PS_: Sadly I had to remove xDebug as swoole wont work if xDebug is installed and enabled

## Image description

This image contain php-7.2 based on alpine with MySQL, PostgreSQL, Redis, GD, [Swoole](https://www.swoole.co.uk/#get-started) enabled and Composer already installed

## Runing the image:

Then run the docker and specify the env file that you have created like this

```
docker run --env-file .env zaherg/php72-swoole:cli
```

## Installed modules information

It has the following modules:

[PHP Modules]

1. Core 
1. ctype  
1. curl 
1. date 
1. dom  
1. fileinfo 
1. filter 
1. ftp  
1. gd 
1. hash 
1. iconv  
1. intl 
1. json 
1. libxml 
1. mbstring 
1. mysqlnd  
1. openssl   
1. pcre 
1. PDO  
1. pdo_mysql  
1. pdo_pgsql  
1. pdo_sqlite 
1. pgsql 
1. Phar 
1. posix  
1. readline 
1. redis  
1. Reflection 
1. session  
1. SimpleXML  
1. sodium
1. SPL  
1. sqlite3  
1. standard 
1. swoole
1. tokenizer  
1. xml  
1. xmlreader  
1. xmlwriter  
1. zip  
1. zlib 

## GD information

```
GD Support => enabled
GD Version => bundled (2.1.0 compatible)
FreeType Support => enabled
FreeType Linkage => with freetype
FreeType Version => 2.8.1
GIF Read Support => enabled
GIF Create Support => enabled
JPEG Support => enabled
libJPEG Version => 8
PNG Support => enabled
libPNG Version => 1.6.34
WBMP Support => enabled
XBM Support => enabled

Directive => Local Value => Master Value
gd.jpeg_ignore_warning => 1 => 1
```
