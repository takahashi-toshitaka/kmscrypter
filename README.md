# kmscrypter
AWS assume role credential wrapper.


[![Go Report Card](https://goreportcard.com/badge/github.com/masahide/kmscrypter)](https://goreportcard.com/report/github.com/masahide/kmscrypter)
[![Build Status](https://travis-ci.org/masahide/kmscrypter.svg?branch=master)](https://travis-ci.org/masahide/kmscrypter)
[![codecov](https://codecov.io/gh/masahide/kmscrypter/branch/master/graph/badge.svg)](https://codecov.io/gh/masahide/kmscrypter)
[![goreleaser](https://img.shields.io/badge/powered%20by-goreleaser-green.svg?style=flat-square)](https://github.com/goreleaser)

## Description

kmscrypter is use aws kms to encrypt and decrypt it and set it to environment variable.

## Installation

### Linux

For RHEL/CentOS:

```bash
sudo yum install https://github.com/masahide/kmscrypter/releases/download/v0.1.x/kmscrypter_amd64.rpm
```

For Ubuntu/Debian:

```bash
wget -qO /tmp/kmscrypter_amd64.deb https://github.com/masahide/kmscrypter/releases/download/v0.1.x/kmscrypter_amd64.deb && sudo dpkg -i /tmp/kmscrypter_amd64.deb
```

### macOS


install via [brew](https://brew.sh):

```bash
brew tap masahide/kmscrypter https://github.com/masahide/kmscrypter
brew install kmscrypter
```


## Usage


