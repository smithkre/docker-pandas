# Pandas

![version](https://img.shields.io/docker/v/amancevice/pandas?color=blue&label=version&logo=docker&logoColor=eee&sort=semver&style=flat-square)
[![latest](https://img.shields.io/github/workflow/status/amancevice/docker-pandas/build?logo=github&style=flat-square)](https://github.com/amancevice/docker-pandas/actions)

Docker image with [pandas](https://github.com/pandas-dev/pandas) installed.

_Note: images using Python 2.7 are no longer supported_

For `Python 3.6` version

## Pulling

Pull image tags with the `pandas` version you wish to use:

```bash
docker pull amancevice/pandas:x.y.z
```

For slim images append `-slim` to the tag:

```bash
docker pull amancevice/pandas:x.y.z-slim
```

For alpine-based images append `-alpine` to the tag:

```bash
docker pull amancevice/pandas:x.y.z-alpine
```

## Building

Use the `make` command to build a new suite of pandas images:

```bash
make
```
