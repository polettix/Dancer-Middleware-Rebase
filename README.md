NAME
====

Dancer::Middleware::Rebase - a Plack middleware to be used for Dancer

SYNOPSIS
========

In your config.yml configuration file for Dancer:

    plack_middlewares:
       -
          - "+Dancer::Middleware::Rebase"
          - base
          - "http://example.com/app"
          - strip
          - 1

Please note that you have to put a plus sign before the module name,
otherwise Plack will think that it is a name to be referred to the
Plack::Middleware namespace.


ALL THE REST
============

Want to know more? [See the module’s documentation](http://search.cpan.org/perldoc?Dancer::Middleware::Rebase) to figure out
all the bells and whistles of this module!

Want to install the latest release? [Go fetch it on CPAN](http://search.cpan.org/dist/Dancer-Middleware-Rebase/).

Want to contribute? [Fork it on GitHub](https://github.com/polettix/Dancer-Middleware-Rebase).

That’s all folks!

