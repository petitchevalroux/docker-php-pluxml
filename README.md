# PluXml in Docker
Available on:
* [docker hub](https://registry.hub.docker.com/u/petitchevalroux/php-pluxml/)
* [github](https://github.com/petitchevalroux/docker-php-pluxml)

Docker php-pluxml container use to package php applications

([nginx-php](https://github.com/petitchevalroux/docker-nginx-php)) <-> ([php-fpm](https://github.com/petitchevalroux/docker-php-fpm) + pluxml)

## Benchmarks

Benchmarks are run with ab on a Mackbook Air:

```bash
ab -c 100 -n 1000 http://192.168.59.103:8080/install.php
```
Benchmarks are available [here](https://github.com/petitchevalroux/docker-php-pluxml/tree/master/bench)

## About me
http://petitchevalroux.net