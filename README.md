# Docker-compose

This build step invokes `docker-compose` commands in [Google Cloud Build](cloud.google.com/cloud-build/).

Arguments passed to this builder will be passed to `docker-compose` directly,
allowing callers to run [any docker-compose
command](https://docs.docker.com/compose/reference/overview/).

## Examples

See examples in the `examples` subdirectory.

## Reference
[github.com/GoogleCloudPlatform/cloud-builders-community](https://github.com/GoogleCloudPlatform/cloud-builders-community/tree/master/docker-compose)
