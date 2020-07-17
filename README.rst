=======
Pymaven
=======

Overview
========

Pymaven is a Python library for interfacing with the maven build system. There
are two major interfaces:

* pymaven.client provides a basic maven repository client
* pymaven.pom provides a Pom object that can provide progromatic access to
  a maven pom file



To test locally with tox:

```
CFLAGS="-I$(brew --prefix openssl)/include" \
LDFLAGS="-L$(brew --prefix openssl)/lib" \
pyenv install -v 3.5.0
pyenv install -v 3.6.0
...
brew install python
```


To configure Slack - Travis integration...
```
https://slack.com/signin?redir=/services/new/travis
```

I selected `lecafeautomatique` and created a `builds` channel