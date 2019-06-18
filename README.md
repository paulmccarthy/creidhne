# Introduction

Creidhne is a bash script used to create the base directory structure and files that I like to use for NodeJS projects.

It's not designed to be a tool to suit everyones needs, but it's useful when starting a new project.

[Creidhne](https://en.wikipedia.org/wiki/Creidhne) was the goldsmith of the Tuatha Dé Danann.

# Usage

```
$ build -h

Usage: build [OPTIONS]

Options
  -p <install path>                 The directory to install into. Defaults to current directory.
  -i                                Ignore non-empty install directory.
  -r                                Remove all files in install directory. Implies -i.
  -j                                Include package.json
  -h                                This help message.
  -g <remote>                       Initialise git and configure remote.

```

# Bugs/ Issues
Report any bugs or issues via [Github Issues Page](https://github.com/paulmccarthy/creidhne/issues)
