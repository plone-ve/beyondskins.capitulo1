=====================
beyondskins.capitulo1
=====================

Introduction
============

Beyondskins capitulo1 Theme is an installable Plone Theme developed by 
`Simples Consultoria`_ using the **theming** and **packaging** 
features available in `plone.app.theming`_.

.. image:: https://github.com/agnogueira/beyondskins.capitulo1/raw/master/docs/logo.png


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/agnogueira/beyondskins.capitulo1/raw/master/beyondskins/capitulo1/static/preview.png


Features
========

- It's an installable Plone Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Zip file
--------

If you are an end user, you might enjoy installation via zip file import.

1. Download a `zip file <https://github.com/agnogueira/beyondskins.capitulo1/raw/master/beyondskins.capitulo1.zip>`_.
2. Import the theme from the Diazo theme control panel.

Enabling the theme
^^^^^^^^^^^^^^^^^^

Select and enable the theme from the Diazo control panel. That's it!


Buildout
--------

If you are a developer, you might enjoy installing it via buildout.

For install ``beyondskins.capitulo1`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        beyondskins.capitulo1


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'beyondskins.capitulo1',
    ],


Contribute
==========

- Issue Tracker: https://github.com/agnogueira/beyondskins.capitulo1/issues
- Source Code: https://github.com/agnogueira/beyondskins.capitulo1


License
=======

The project is licensed under the GPLv2.

Credits
-------

- Andre Nogueira (agnogueira at gmail dot com).


Amazing contributions
---------------------

- Leonardo J. Caballero G. aka macagua (leonardocaballero at gmail dot com).

You can find an updated list of package contributors on https://github.com/agnogueira/beyondskins.capitulo1/contributors

.. _`Simples Consultoria`: http://www.simplesconsultoria.com.br/
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
