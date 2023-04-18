# Simple Node.js program

This is to build an application image for a simple Node.js program. This would be very similar for many other dynamic languages, like Python or Ruby.

## Build application images with Docker

1. Run `$ docker build -t simple-node .`
2. Run `$ docker run --rm -p 3001:3001 simple-node`
