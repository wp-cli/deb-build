deb-build
=========

[![Build Status](https://travis-ci.org/wp-cli/deb-build.svg?branch=master)](https://travis-ci.org/wp-cli/deb-build)

Builds a Debian build of the latest stable WP-CLI release using [utils/wp-cli-updatedeb.sh](https://raw.githubusercontent.com/wp-cli/wp-cli/master/utils/wp-cli-updatedeb.sh).

To generate a new Debian build, trigger a Travis build on the repo (either by restarting an existing build or making some non-functional change).

This is run outside the main project repo to keep it as an isolated process.
