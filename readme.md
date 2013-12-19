
# NodeJS

This creates an Ubuntu derived base image that installs a recent version of Node.js.
As of Dec 12, 2013, Node.js version is 0.10.23.

This image can be used as a standalone, or a base image for others.

## Usage

Standalone
```sh
docker run -i -t truongsinh/nodejs
```

Based image for other builds

```
#…

FROM truongsinh/nodejs

#…
```
