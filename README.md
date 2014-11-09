# Install Docker

A quick one liner to install the latest version of Docker on CentOS 7 / RHEL 7 server.

## Pre-Compiled Binaries

This will remove the standard repository version of Docker and replace it with the lastest version of the pre-Compiled Binaries from [Docker](https://docs.docker.com/installation/centos/#manual-installation-of-latest-version).

```bash
curl -fsS https://raw2.github.com/russmckendrick/docker-install/master/install-bins | bash
```

## Using Goldman Repo

It will remove the standard repository version of Docker and replace it with the latest build from the "[goldmann-docker-io](https://copr.fedoraproject.org/coprs/goldmann/docker-io/)" repo;

```bash
curl -fsS https://raw2.github.com/russmckendrick/docker-install/master/install-goldman | bash
```