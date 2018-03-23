# pythonselenium

Edge

[![Docker Pulls](https://img.shields.io/docker/pulls/neetjn/pythonselenium.svg)](https://hub.docker.com/r/neetjn/pythonselenium/)

Production

[![Docker Pulls](https://img.shields.io/docker/pulls/robotgraves/pythonselenium.svg)](https://hub.docker.com/r/robotgraves/pythonselenium/)

Docker image with Python 2.7, Chrome, Firefox, and their respective webdrivers.

### Versions

* Chrome: v65 stable
* Chromedriver: v2.35
* Firefox: v58
* Geckodriver: v0.19.1

### Usage

**Edge** (currently using pipenv)
```
FROM neetjn/pythonselenium:latest
```

or

**Production**
```
FROM robotgraves/pythonselenium:latest
```

---
Copyright (c) 2017 Alex Paul, John Nolette Licensed under the MIT license.