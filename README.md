# Fast Data Science aka `fds`

[![CircleCI](https://circleci.com/gh/mohithg/furious-flemingo.svg?style=svg)](https://app.circleci.com/pipelines/github/mohithg/furious-flemingo)

[![PyPI version](https://badge.fury.io/py/furiousflemingo-mohithg.svg)](https://badge.fury.io/py/furiousflemingo-mohithg)

`fds` is a tool for Data Scientists made by DAGsHub to version control
data and code at once.

At the high level `fds` is a wrapper for Git and DVC. So Data Scientists
can use `fds` instead of `git` and `dvc` separately.

## Commands Supported

| Syntax | Description               | Status      |
|--------|---------------------------|-------------|
| init   | Initializes git and dvc   | Done        |
| status | Get status of git and dvc | Done        |

## Installation

- Install `fds` using PIP `pip install furiousflemingo-mohithg`
- Once installed successfully, you can start using `fds`
- eg: `fds init` should trigger the init command

## Docker support

- To run `fds` with docker, first pull the docker image
`docker pull mohithg/furiousflemingo`

- Then run with docker
`docker run mohithg/furiousflemingo <supported_command>`
