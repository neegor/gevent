Py3 Gevent
=======

100% compatibility with the official gevent

Features include:

* Fast event loop based on libev_.
* Lightweight execution units based on greenlet_.
* Familiar API that re-uses concepts from the Python standard library.
* Cooperative sockets with SSL support.
* DNS queries performed through c-ares_ or a threadpool.
* Ability to use standard library and 3rd party modules written for standard blocking sockets


installing from github
----------------------

To install the latest development version:

  pip install cython git+git://github.com/neegor/gevent.git#egg=gevent
