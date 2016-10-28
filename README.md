# py2deb-docker
Docker image for py2deb https://py2deb.readthedocs.org

## Usage

``` shell
docker run --rm -v `pwd`:/tmp -i py2deb <pip package name>
```

The debian packages will be in your current directory.
