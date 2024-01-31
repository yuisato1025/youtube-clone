# youtube-clone

## Overview

Youtube clone app.

This is sourced by https://neetcode.io/courses/full-stack-dev.

## Docker Usage

- Build a docker image

```sh
docker build -t [region]-docker.pkg.dev/[PROJECT_ID]/video-processing-repo/video-processing-service ./video-processing-service --platform linux/amd64
```

- Push the image to Aritifact Registry

```sh
docker push [region]-docker.pkg.dev/[PROJECT_ID]/video-processing-repo/video-processing-service
```
