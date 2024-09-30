# Intro

Basketbot is a bot for Twitch.

# Installing

# Configuration

# Known Issues and Bugs

# Building

## Prerequisites For Building

The build has a couple prereqs:
* [Homebrew](https://brew.sh/) is needed for the `brew install` commands below.
* A golang compiler that supports multiple architectures and operating systems. On a Mac, you get this with `brew install go`
* [Task](https://taskfile.dev/) need to be installed. Easily done with `brew install go-task` on a Mac.

## Binaries

In the root directory of the repo, run `task build-all-binaries`. This will build the binaries for each supported operating system and CPU combination.
