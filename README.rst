========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-py-pkg-tool/badge/?style=flat
    :target: https://readthedocs.org/projects/python-py-pkg-tool
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/python-py-pkg-tool.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/python-py-pkg-tool

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/python-py-pkg-tool?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/python-py-pkg-tool

.. |requires| image:: https://requires.io/github/techdragon/python-py-pkg-tool/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/python-py-pkg-tool/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/techdragon/python-py-pkg-tool/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/techdragon/python-py-pkg-tool

.. |codecov| image:: https://codecov.io/github/techdragon/python-py-pkg-tool/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/python-py-pkg-tool

.. |landscape| image:: https://landscape.io/github/techdragon/python-py-pkg-tool/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/python-py-pkg-tool/master
    :alt: Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/techdragon/python-py-pkg-tool/badges/gpa.svg
   :target: https://codeclimate.com/github/techdragon/python-py-pkg-tool
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/py-pkg-tool.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/py-pkg-tool

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/python-py-pkg-tool/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/python-py-pkg-tool/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/py-pkg-tool.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/py-pkg-tool

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/py-pkg-tool.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/py-pkg-tool

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/py-pkg-tool.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/py-pkg-tool

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/techdragon/python-py-pkg-tool/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/techdragon/python-py-pkg-tool/


.. end-badges

A swiss army knife for working with python packages.

* Free software: MIT license

Installation
============

::

    pip install py-pkg-tool

Documentation
=============

https://python-py-pkg-tool.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
