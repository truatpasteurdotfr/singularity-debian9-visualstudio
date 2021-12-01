# building a vstudio on debian9 toy system for singularity for CI

Tru <tru@pasteur.fr>

## Why ?
- toy system for github actions
- build singularity container from dockerhub registry and push to oras://ghcr.io with proper tags 
- 
## Caveat
- playground, use at your own risk!
- `:latest` tagged singularity image

## Usage

- Singularity [![Singularity build](https://github.com/truatpasteurdotfr/singularity-debian9-visualstudio/actions/workflows/singularity-publish.yml/badge.svg)](https://github.com/truatpasteurdotfr/singularity-debian9-visualstudio/actions/workflows/singularity-publish.yml)
```
singularity run -B /run  oras://ghcr.io/truatpasteurdotfr/singularity-debian9-visualstudio:latest
```
