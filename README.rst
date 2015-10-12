==========
 NoFapBot
==========

This is an IRC bot that aims at helping people measure their NoFap_ streaks.

.. _NoFap: https://www.reddit.com/r/NoFap/wiki/index

Requirements
=============

The bot is written in Groovy_, so you need a Groovy interpreter to run it. It
has been tested with Groovy 2.4, so at least this version should work.

.. _Groovy: http://groovy-lang.org/

The very first time that it is run, it also requires an Internet connection to
download its dependencies from `Maven Central`_ (unless you happen to have
another way to make them available to `the Grape dependency manager`_).

.. _Maven Central: http://central.sonatype.org/
.. _the Grape dependency manager: http://docs.groovy-lang.org/2.4.5/html/documentation/grape.html

Configuration files
====================

To know what servers to connect to, the bot uses YAML_ configuration files. You
can use the provided example, ``freenode.cfg``, as a starting point for your own
configuration files.

.. _YAML: http://yaml.org/
