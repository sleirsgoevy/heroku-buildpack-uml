# heroku-buildpack-uml
Heroku buildpack for User-Mode Linux.

# Note: this Heroku build pack no longer works! Heroku has changed there security policies to deny the ptrace() system call which UML relies upon.
All the binaries (e.g. UML itself and slirp) were taken from Debian 8 "jessie" repositories. There's no need to mirror them.
