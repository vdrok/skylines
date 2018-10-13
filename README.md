# SkyLines

*SkyLines* is a web platform where pilots can share their flights with others
after, or even during flight via live tracking.  *SkyLines* is a sort of social
network for pilots including rankings, statistics and other interesting
features.  Most of all *SkyLines* is truly open in all regards compared to
other similar platforms.

*SkyLines* has started development in 2012 as a spin-off from the popular
[XCSoar](http://www.xcsoar.org/) glide computer. Internally *SkyLines* is still
sharing some code with XCSoar in the algorithmic areas and is providing the
base for XCSoar's live tracking functionalities.

*SkyLines* is far from finished yet, but it has been running in production for
quite some time now. You can reach the official server at
<http://www.skylines.aero>.

Build Status: [![Build Status](https://travis-ci.org/skylines-project/skylines.png?branch=master)](https://travis-ci.org/skylines-project/skylines)


## Installation and Setup

*SkyLines* is based on Python and depends on the following major components:

* [PostgreSQL](http://www.postgresql.org/) database with
  [PostGIS 2.x](http://www.postgis.net/) extension
* [Flask](http://flask.pocoo.org/) web application microframework for Python
* [SQLAlchemy](http://www.sqlalchemy.org/) ORM framework with
  [GeoAlchemy 2](https://geoalchemy-2.readthedocs.org) extension
* [gevent](http://www.gevent.org/) coroutine-based network library for Python (used for
  the live tracking server)

The process of installing these components and setting up a server for local
development is described in the [INSTALL.md](INSTALL.md) file.

