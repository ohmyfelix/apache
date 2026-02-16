# Apache

Ready-to-use Apache (httpd) Docker image based on Debian Jessie.

-----

[![Docker Stars](https://img.shields.io/docker/stars/dockette/apache.svg?style=flat)](https://hub.docker.com/r/dockette/apache/)
[![Docker Pulls](https://img.shields.io/docker/pulls/dockette/apache.svg?style=flat)](https://hub.docker.com/r/dockette/apache/)

## Discussion / Help

[![Join the chat](https://img.shields.io/gitter/room/dockette/dockette.svg?style=flat-square)](https://gitter.im/dockette/dockette?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Usage

### Simple

```
docker run -v /path/to/site:/srv dockette/apache
```

### Sites

```
docker run \
	-v /path/to/site:/srv \
	-v mysite.conf:/etc/apache2/sites-enabled/mysite.conf
	dockette/apache
```

## Maintenance
See [how to contribute](https://github.com/dockette/.github/blob/master/CONTRIBUTING.md) to this package. Consider to [support](https://github.com/sponsors/f3l1x) **f3l1x**. Thank you for using this package.
