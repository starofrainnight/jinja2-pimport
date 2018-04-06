===============
Jinja2 PImport
===============

Jinja2 Extension for Python Import keywords

So we don't have to write a new jinja2 filter just for simple function.

It exposed a powerful weapon for shoot you feet, use it in your own risk!

Usage
-------

Get the user name from git config

.. code::

    "full_name": "{{ ('subprocess'|pimport).check_output('git config --global user.name', shell=True).strip().decode() }}"

License
-------

Distributed under the terms of the `MIT`_ license, jinja2-pimport is free and open source software

.. image:: https://opensource.org/trademarks/osi-certified/web/osi-certified-120x100.png
   :align: left
   :alt: OSI certified
   :target: https://opensource.org/

.. _`MIT`: http://opensource.org/licenses/MIT
