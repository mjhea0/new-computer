# New Computer Setup

Steps I go through when setting up a new Mac...

## Download and Install

1. Chrome
1. iTerm2
1. Spectacle
1. Caffeine App
1. Postgres.app
1. Slack
1. Skype
1. Spotify
1. Thunderbird
1. Docker
1. Fibit Connect
1. Filezilla
1. Libre Office
1. Mou

## Atom

1. Download and install
1. The `atom` shell command may need to be installed `Atom > Install Shell Commands`
1. [Configure](http://mherman.org/blog/2016/08/16/atom-for-web-developers/#.WBjTdJMrJE4)

## Brew

Install and then update:

```sh
$ brew update && brew doctor
```

## zsh

zsh should already be installed:

```sh
$ zsh --version
```

Install 'Oh My Zsh'

## Git

Install:

```sh
$ brew install git
```

Update config:

```sh
$ git config --global user.name 'YOUR FULL NAME FROM GITHUB'
$ git config --global user.email 'YOUR EMAIL ADDRESS FROM GITHUB'
```

## Install Node and NPM

```sh
$ brew install node
```

Ensure you don't need sudo to install packages:

```sh
$ npm i express -g
```

## Install Python

```sh
$ brew install python3
```

Ensure you don't need sudo to install packages:

```sh
$ pip3 install django
```

## Retire Old Repos (if necessary)

1. Ensure all repos do not have [uncommitted changes](https://github.com/brandon-rhodes/uncommitted)
1. Ensure all repos have been pushed to Github
