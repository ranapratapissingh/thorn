.. _contributing:

==============
 Contributing
==============

Welcome!

This document is fairly extensive and you are not really expected
to study this in detail for small contributions;

    The most important rule is that contributing must be easy
    and that the community is friendly and not nitpicking on details
    such as coding style.

If you're reporting a bug you should read the Reporting bugs section
below to ensure that your bug report contains enough information
to successfully diagnose the issue, and if you're contributing code
you should try to mimic the conventions you see surrounding the code
you are working on, but in the end all patches will be cleaned up by
the person merging the changes so don't worry too much.

.. contents::
    :local:

.. _community-code-of-conduct:

Community Code of Conduct
=========================

The goal is to maintain a diverse community that is pleasant for everyone.
That is why we would greatly appreciate it if everyone contributing to and
interacting with the community also followed this Code of Conduct.

The Code of Conduct covers our behavior as members of the community,
in any forum, mailing list, wiki, website, Internet relay chat (IRC), public
meeting or private correspondence.

The Code of Conduct is heavily based on the `Ubuntu Code of Conduct`_, and
the `Pylons Code of Conduct`_.

.. _`Ubuntu Code of Conduct`: http://www.ubuntu.com/community/conduct
.. _`Pylons Code of Conduct`: http://docs.pylonshq.com/community/conduct.html

Be considerate.
---------------

Your work will be used by other people, and you in turn will depend on the
work of others.  Any decision you take will affect users and colleagues, and
we expect you to take those consequences into account when making decisions.
Even if it's not obvious at the time, our contributions to Thorn will impact
the work of others.  For example, changes to code, infrastructure, policy,
documentation and translations during a release may negatively impact
others work.

Be respectful.
--------------

The Thorn community and its members treat one another with respect.  Everyone
can make a valuable contribution to Thorn.  We may not always agree, but
disagreement is no excuse for poor behavior and poor manners.  We might all
experience some frustration now and then, but we cannot allow that frustration
to turn into a personal attack.  It's important to remember that a community
where people feel uncomfortable or threatened is not a productive one.  We
expect members of the Thorn community to be respectful when dealing with
other contributors as well as with people outside the Thorn project and with
users of Thorn.

Be collaborative.
-----------------

Collaboration is central to Thorn and to the larger free software community.
We should always be open to collaboration.  Your work should be done
transparently and patches from Thorn should be given back to the community
when they are made, not just when the distribution releases.  If you wish
to work on new code for existing upstream projects, at least keep those
projects informed of your ideas and progress.  It many not be possible to
get consensus from upstream, or even from your colleagues about the correct
implementation for an idea, so don't feel obliged to have that agreement
before you begin, but at least keep the outside world informed of your work,
and publish your work in a way that allows outsiders to test, discuss and
contribute to your efforts.

When you disagree, consult others.
----------------------------------

Disagreements, both political and technical, happen all the time and
the Thorn community is no exception.  It is important that we resolve
disagreements and differing views constructively and with the help of the
community and community process.  If you really want to go a different
way, then we encourage you to make a derivative distribution or alternate
set of packages that still build on the work we've done to utilize as common
of a core as possible.

When you are unsure, ask for help.
----------------------------------

Nobody knows everything, and nobody is expected to be perfect.  Asking
questions avoids many problems down the road, and so questions are
encouraged.  Those who are asked questions should be responsive and helpful.
However, when asking a question, care must be taken to do so in an appropriate
forum.

Step down considerately.
------------------------

Developers on every project come and go and Thorn is no different.  When you
leave or disengage from the project, in whole or in part, we ask that you do
so in a way that minimizes disruption to the project.  This means you should
tell people you are leaving and take the proper steps to ensure that others
can pick up where you leave off.

.. _reporting-bugs:


Reporting Bugs
==============

.. _vulnsec:

Security
--------

You must never report security related issues, vulnerabilities or bugs
including sensitive information to the bug tracker, or elsewhere in public.
Instead sensitive bugs must be sent by email to ``security@robinhood.com``.

If you'd like to submit the information encrypted our PGP key is::

    -----BEGIN PGP PUBLIC KEY BLOCK-----
    Version: GnuPG v1.4.15 (Darwin)

    mQENBFJpWDkBCADFIc9/Fpgse4owLNvsTC7GYfnJL19XO0hnL99sPx+DPbfr+cSE
    9wiU+Wp2TfUX7pCLEGrODiEP6ZCZbgtiPgId+JYvMxpP6GXbjiIlHRw1EQNH8RlX
    cVxy3rQfVv8PGGiJuyBBjxzvETHW25htVAZ5TI1+CkxmuyyEYqgZN2fNd0wEU19D
    +c10G1gSECbCQTCbacLSzdpngAt1Gkrc96r7wGHBBSvDaGDD2pFSkVuTLMbIRrVp
    lnKOPMsUijiip2EMr2DvfuXiUIUvaqInTPNWkDynLoh69ib5xC19CSVLONjkKBsr
    Pe+qAY29liBatatpXsydY7GIUzyBT3MzgMJlABEBAAG0MUNlbGVyeSBTZWN1cml0
    eSBUZWFtIDxzZWN1cml0eUBjZWxlcnlwcm9qZWN0Lm9yZz6JATgEEwECACIFAlJp
    WDkCGwMGCwkIBwMCBhUIAgkKCwQWAgMBAh4BAheAAAoJEOArFOUDCicIw1IH/26f
    CViDC7/P13jr+srRdjAsWvQztia9HmTlY8cUnbmkR9w6b6j3F2ayw8VhkyFWgYEJ
    wtPBv8mHKADiVSFARS+0yGsfCkia5wDSQuIv6XqRlIrXUyqJbmF4NUFTyCZYoh+C
    ZiQpN9xGhFPr5QDlMx2izWg1rvWlG1jY2Es1v/xED3AeCOB1eUGvRe/uJHKjGv7J
    rj0pFcptZX+WDF22AN235WYwgJM6TrNfSu8sv8vNAQOVnsKcgsqhuwomSGsOfMQj
    LFzIn95MKBBU1G5wOs7JtwiV9jefGqJGBO2FAvOVbvPdK/saSnB+7K36dQcIHqms
    5hU4Xj0RIJiod5idlRC5AQ0EUmlYOQEIAJs8OwHMkrdcvy9kk2HBVbdqhgAREMKy
    gmphDp7prRL9FqSY/dKpCbG0u82zyJypdb7QiaQ5pfPzPpQcd2dIcohkkh7G3E+e
    hS2L9AXHpwR26/PzMBXyr2iNnNc4vTksHvGVDxzFnRpka6vbI/hrrZmYNYh9EAiv
    uhE54b3/XhXwFgHjZXb9i8hgJ3nsO0pRwvUAM1bRGMbvf8e9F+kqgV0yWYNnh6QL
    4Vpl1+epqp2RKPHyNQftbQyrAHXT9kQF9pPlx013MKYaFTADscuAp4T3dy7xmiwS
    crqMbZLzfrxfFOsNxTUGE5vmJCcm+mybAtRo4aV6ACohAO9NevMx8pUAEQEAAYkB
    HwQYAQIACQUCUmlYOQIbDAAKCRDgKxTlAwonCNFbB/9esir/f7TufE+isNqErzR/
    aZKZo2WzZR9c75kbqo6J6DYuUHe6xI0OZ2qZ60iABDEZAiNXGulysFLCiPdatQ8x
    8zt3DF9BMkEck54ZvAjpNSern6zfZb1jPYWZq3TKxlTs/GuCgBAuV4i5vDTZ7xK/
    aF+OFY5zN7ciZHkqLgMiTZ+RhqRcK6FhVBP/Y7d9NlBOcDBTxxE1ZO1ute6n7guJ
    ciw4hfoRk8qNN19szZuq3UU64zpkM2sBsIFM9tGF2FADRxiOaOWZHmIyVZriPFqW
    RUwjSjs7jBVNq0Vy4fCu/5+e+XLOUBOoqtM5W7ELt0t1w9tXebtPEetV86in8fU2
    =0chn
    -----END PGP PUBLIC KEY BLOCK-----

Other bugs
----------

Bugs can always be described to the `mailing-list`_, but the best
way to report an issue and to ensure a timely response is to use the
issue tracker.

1) **Create a GitHub account.**

You need to `create a GitHub account`_ to be able to create new issues
and participate in the discussion.

.. _`create a GitHub account`: https://github.com/signup/free

2) **Determine if your bug is really a bug.**

You should not file a bug if you are requesting support.  For that you can use
the `mailing-list`_, or `irc-channel`_.

3) **Make sure your bug hasn't already been reported.**

Search through the appropriate Issue tracker.  If a bug like yours was found,
check if you have new information that could be reported to help
the developers fix the bug.

4) **Check if you're using the latest version.**

A bug could be fixed by some other improvements and fixes - it might not have an
existing report in the bug tracker. Make sure you're using the latest release of
Thorn, and try the development version to see if the issue is already fixed
and pending release.

5) **Collect information about the bug.**

To have the best chance of having a bug fixed, we need to be able to easily
reproduce the conditions that caused it.  Most of the time this information
will be from a Python traceback message, though some bugs might be in design,
spelling or other errors on the website/docs/code.

    A) If the error is from a Python traceback, include it in the bug report.

    B) We also need to know what platform you're running (Windows, macOS, Linux,
       etc.), the version of your Python interpreter, and the version of Thorn,
       and related packages that you were running when the bug occurred.

6) **Submit the bug.**

By default `GitHub`_ will email you to let you know when new comments have
been made on your bug. In the event you've turned this feature off, you
should check back on occasion to ensure you don't miss any questions a
developer trying to fix the bug might ask.

.. _`GitHub`: https://github.com

.. _issue-tracker:

Issue Tracker
-------------

The Thorn issue tracker can be found at GitHub:
https://github.com/robinhood/thorn

.. _versions:

Versions
========

Version numbers consists of a major version, minor version and a release number,
and conforms to the SemVer versioning spec: http://semver.org.

Stable releases are published at PyPI
while development releases are only available in the GitHub git repository as tags.
All version tags starts with “v”, so version 0.8.0 is the tag v0.8.0.

.. _git-branches:

Branches
========

Current active version branches:

* master (https://github.com/robinhood/thorn/tree/master)

You can see the state of any branch by looking at the Changelog:

    https://github.com/robinhood/thorn/blob/master/Changelog

If the branch is in active development the topmost version info should
contain meta-data like:

::

    2.4.0
    ======
    :release-date: TBA
    :status: DEVELOPMENT
    :branch: master

The ``status`` field can be one of:

* ``PLANNING``

    The branch is currently experimental and in the planning stage.

* ``DEVELOPMENT``

    The branch is in active development, but the test suite should
    be passing and the product should be working and possible for users to test.

* ``FROZEN``

    The branch is frozen, and no more features will be accepted.
    When a branch is frozen the focus is on testing the version as much
    as possible before it is released.

``master`` branch
-----------------

The master branch is where development of the next version happens.

Maintenance branches
--------------------

Maintenance branches are named after the version, e.g. the maintenance branch
for the 2.2.x series is named ``2.2``.  Previously these were named
``releaseXX-maint``.

The versions we currently maintain is:

* 1.0

  This is the current series.

Archived branches
-----------------

Archived branches are kept for preserving history only,
and theoretically someone could provide patches for these if they depend
on a series that is no longer officially supported.

An archived version is named ``X.Y-archived``.

Thorn does not currently have any archived branches.


Feature branches
----------------

Major new features are worked on in dedicated branches.
There is no strict naming requirement for these branches.

Feature branches are removed once they have been merged into a release branch.

Tags
====

Tags are used exclusively for tagging releases.  A release tag is
named with the format ``vX.Y.Z``, e.g. ``v2.3.1``.
Experimental releases contain an additional identifier ``vX.Y.Z-id``, e.g.
``v3.0.0-rc1``.  Experimental tags may be removed after the official release.

.. _contributing-changes:

Working on Features & Patches
=============================

.. note::

    Contributing to Thorn should be as simple as possible,
    so none of these steps should be considered mandatory.

    You can even send in patches by email if that is your preferred
    work method. We won't like you any less, any contribution you make
    is always appreciated!

    However following these steps may make maintainers life easier,
    and may mean that your changes will be accepted sooner.

Forking and setting up the repository
-------------------------------------

First you need to fork the Thorn repository, a good introduction to this
is in the GitHub Guide: `Fork a Repo`_.

After you have cloned the repository you should checkout your copy
to a directory on your machine:

::

    $ git clone git@github.com:username/thorn.git

When the repository is cloned enter the directory to set up easy access
to upstream changes:

::

    $ cd thorn
    $ git remote add upstream git://github.com/robinhood/thorn.git
    $ git fetch upstream

If you need to pull in new changes from upstream you should
always use the ``--rebase`` option to ``git pull``:

::

    git pull --rebase upstream master

With this option you don't clutter the history with merging
commit notes. See `Rebasing merge commits in git`_.
If you want to learn more about rebasing see the `Rebase`_
section in the GitHub guides.

If you need to work on a different branch than ``master`` you can
fetch and checkout a remote branch like this::

    git checkout --track -b 3.0-devel origin/3.0-devel

.. _`Fork a Repo`: http://help.github.com/fork-a-repo/
.. _`Rebasing merge commits in git`:
    http://notes.envato.com/developers/rebasing-merge-commits-in-git/
.. _`Rebase`: http://help.github.com/rebase/

.. _contributing-testing:

Running the unit test suite
---------------------------

To run the Thorn test suite you need to install a few dependencies.
A complete list of the dependencies needed are located in
``requirements/test.txt``.

If you're working on the development version, then you need to
install the development requirements first:

::

    $ pip install -U -r requirements/dev.txt

Both the stable and the development version have testing related
dependencies, so install these next:

::

    $ pip install -U -r requirements/test.txt
    $ pip install -U -r requirements/default.txt

After installing the dependencies required, you can now execute
the test suite by calling:

::

    $ python setup.py test

This will run all of the test, to run individual tests
you can call ``py.test`` directly:

::

    $ py.test

Some useful options to ``py.test`` are:

* ``-x``

    Stop running the tests at the first test that fails.

* ``-s``

    Don't capture output

If you want to run the tests for a single test file only
you can do so like this:

::

    $ py.test t/unit/test_request.py

Running the functional test suite
---------------------------------

Thorn uses ``cyanide`` for functional/integration tests,
but note that this requires a working Celery installation.

#. Start the celery worker:

    ::

        $ celery -A thorn.funtests worker -l info -P eventlet -c 1000

#. Start the development web server:

    ::

        $ python manage.py runserver)

#. Then execute the functional test suite:

    ::

        $ celery -A thorn.funtests cyanide

For a list of tests that you can select see:

    ::

        $ celery -A thorn.funtests cyanide -l


.. _contributing-pull-requests:

Creating pull requests
----------------------

When your feature/bugfix is complete you may want to submit
a pull requests so that it can be reviewed by the maintainers.

Creating pull requests is easy, and also let you track the progress
of your contribution.  Read the `Pull Requests`_ section in the GitHub
Guide to learn how this is done.

You can also attach pull requests to existing issues by following
the steps outlined here: http://bit.ly/koJoso

.. _`Pull Requests`: http://help.github.com/send-pull-requests/

.. _contributing-coverage:

Calculating test coverage
~~~~~~~~~~~~~~~~~~~~~~~~~

To calculate test coverage you must first install the ``coverage`` module.

Installing the ``coverage`` module:

::

    $ pip install -U coverage

Code coverage in HTML:

::

    $ make cov

The coverage output will then be located at
``cover/index.html``.

.. _contributing-tox:

Running the tests on all supported Python versions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

There is a ``tox`` configuration file in the top directory of the
distribution.

To run the tests for all supported Python versions simply execute:

::

    $ tox

Use the ``tox -e`` option if you only want to test specific Python versions:

::

    $ tox -e 2.7

Building the documentation
--------------------------

To build the documentation you need to install the dependencies
listed in ``requirements/docs.txt``:

::

    $ pip install -U -r requirements/docs.txt

After these dependencies are installed you should be able to
build the docs by running:

::

    $ cd docs
    $ rm -rf _build
    $ make html

Make sure there are no errors or warnings in the build output.
After building succeeds the documentation is available at ``_build/html``.

.. _contributing-verify:

Verifying your contribution
---------------------------

To use these tools you need to install a few dependencies.  These dependencies
can be found in ``requirements/pkgutils.txt``.

Installing the dependencies:

::

    $ pip install -U -r requirements/pkgutils.txt

pyflakes & PEP8
~~~~~~~~~~~~~~~

To ensure that your changes conform to PEP8 and to run pyflakes
execute:

::

    $ make flakecheck

To not return a negative exit code when this command fails use
the ``flakes`` target instead:

::

    $ make flakes

API reference
~~~~~~~~~~~~~

To make sure that all modules have a corresponding section in the API
reference please execute:

::

    $ make apicheck
    $ make configcheck

If files are missing you can add them by copying an existing reference file.

If the module is internal it should be part of the internal reference
located in ``docs/internals/reference/``.  If the module is public
it should be located in ``docs/reference/``.

For example if reference is missing for the module ``thorn.awesome``
and this module is considered part of the public API, use the following steps:


Use an existing file as a template:

::

    $ cd docs/reference/
    $ cp thorn.request.rst thorn.awesome.rst

Edit the file using your favorite editor:

::

    $ vim thorn.awesome.rst

        # change every occurrence of ``thorn.request`` to
        # ``thorn.awesome``


Edit the index using your favorite editor:

::

    $ vim index.rst

        # Add ``thorn.awesome`` to the index.


Commit your changes:

::

    # Add the file to git
    $ git add thorn.awesome.rst
    $ git add index.rst
    $ git commit thorn.awesome.rst index.rst \
        -m "Adds reference for thorn.awesome"

.. _coding-style:

Coding Style
============

You should probably be able to pick up the coding style
from surrounding code, but it is a good idea to be aware of the
following conventions.

* All Python code must follow the `PEP-8`_ guidelines.

`pep8.py`_ is an utility you can use to verify that your code
is following the conventions.

.. _`PEP-8`: http://www.python.org/dev/peps/pep-0008/
.. _`pep8.py`: http://pypi.python.org/pypi/pep8

* Docstrings must follow the `PEP-257`_ conventions, and use the following
  style.

    Do this:

    ::

        def method(self, arg):
            """Short description.

            More details.

            """

    or:

    ::

        def method(self, arg):
            """Short description."""


    but not this:

    ::

        def method(self, arg):
            """
            Short description.
            """

.. _`PEP-257`: http://www.python.org/dev/peps/pep-0257/

* Lines should not exceed 78 columns.

  You can enforce this in ``vim`` by setting the ``textwidth`` option:

  ::

        set textwidth=78

  If adhering to this limit makes the code less readable, you have one more
  character to go on, which means 78 is a soft limit, and 79 is the hard
  limit :)

* Import order

    * Python standard library (`import xxx`)
    * Python standard library ('from xxx import`)
    * Third-party packages.
    * Other modules from the current package.

    or in case of code using Django:

    * Python standard library (`import xxx`)
    * Python standard library ('from xxx import`)
    * Third-party packages.
    * Django packages.
    * Other modules from the current package.

    Within these sections the imports should be sorted by module name.

    Example:

    ::

        import threading
        import time

        from collections import deque
        from Queue import Queue, Empty

        from .datastructures import TokenBucket
        from .five import zip_longest, items, range
        from .utils import timeutils

* Wild-card imports must not be used (`from xxx import *`).

* For distributions where Python 2.5 is the oldest support version
  additional rules apply:

    * Absolute imports must be enabled at the top of every module::

        from __future__ import absolute_import

    * If the module uses the ``with`` statement and must be compatible
      with Python 2.5 (thorn is not) then it must also enable that::

        from __future__ import with_statement

    * Every future import must be on its own line, as older Python 2.5
      releases did not support importing multiple features on the
      same future import line::

        # Good
        from __future__ import absolute_import
        from __future__ import with_statement

        # Bad
        from __future__ import absolute_import, with_statement

     (Note that this rule does not apply if the package does not include
     support for Python 2.5)


* Note that we use "new-style` relative imports when the distribution
  does not support Python versions below 2.5

    This requires Python 2.5 or later:

    ::

        from . import submodule


.. _feature-with-extras:

Contributing features requiring additional libraries
====================================================

Some features like a new result backend may require additional libraries
that the user must install.

We use setuptools `extra_requires` for this, and all new optional features
that require third-party libraries must be added.

1) Add a new requirements file in `requirements/extras`

    E.g. for a Cassandra backend this would be
    ``requirements/extras/cassandra.txt``, and the file looks like this:

    ::

        pycassa

    These are pip requirement files so you can have version specifiers and
    multiple packages are separated by newline.  A more complex example could
    be:

    ::

        # pycassa 2.0 breaks Foo
        pycassa>=1.0,<2.0
        thrift

2) Modify ``setup.py``

    After the requirements file is added you need to add it as an option
    to ``setup.py`` in the ``extras_require`` section::

        extra['extras_require'] = {
            # ...
            'cassandra': extras('cassandra.txt'),
        }

3) Document the new feature in ``docs/includes/installation.txt``

    You must add your feature to the list in the Bundles section
    of ``docs/includes/installation.txt``.

    After you've made changes to this file you need to render
    the distro ``README`` file:

    ::

        $ pip install -U requirements/pkgutils.txt
        $ make readme


That's all that needs to be done, but remember that if your feature
adds additional configuration options then these needs to be documented
in ``docs/configuration.rst``.  Also all settings need to be added to the
``thorn/conf.py`` module.

.. _contact_information:

Contacts
========

This is a list of people that can be contacted for questions
regarding the official git repositories, PyPI packages
Read the Docs pages.

If the issue is not an emergency then it is better
to `report an issue`_.


Committers
----------

Ask Solem
~~~~~~~~~

:github: https://github.com/ask
:twitter: http://twitter.com/#!/asksol

.. _packages:

Packages
========

``thorn``
---------

:git: https://github.com/robinhood/thorn
:CI: http://travis-ci.org/#!/robinhood/thorn
:Windows-CI: https://ci.appveyor.com/project/robinhood/thorn
:PyPI: http://pypi.python.org/pypi/thorn
:docs: http://thorn.readthedocs.io

.. _release-procedure:


Release Procedure
=================

Updating the version number
---------------------------

The version number must be updated two places:

    * ``thorn/__init__.py``
    * ``docs/include/introduction.txt``

After you have changed these files you must render
the ``README`` files.  There is a script to convert sphinx syntax
to generic reStructured Text syntax, and the make target `readme`
does this for you:

::

    $ make readme

Now commit the changes:

::

    $ git commit -a -m "Bumps version to X.Y.Z"

and make a new version tag:

::

    $ git tag vX.Y.Z
    $ git push --tags

Releasing
---------

Commands to make a new public stable release:

::

    $ make distcheck  # checks pep8, autodoc index, runs tests and more
    $ make dist  # NOTE: Runs git clean -xdf and removes files not in the repo.
    $ python setup.py sdist upload --sign --identity='Ask Solem'
    $ python setup.py bdist_wheel upload --sign --identity='Ask Solem'

If this is a new release series then you also need to do the
following:

* Go to the Read The Docs management interface at:
    http://readthedocs.org/projects/thorn?fromdocs=thorn

* Enter "Edit project"

    Change default branch to the branch of this series, e.g. ``2.4``
    for series 2.4.

* Also add the previous version under the "versions" tab.

.. _`mailing-list`: http://groups.google.com/group/thorn-users

.. _`irc-channel`: http://docs.celeryproject.org/en/latest/getting-started/resources.html#irc

.. _`report an issue`: http://docs.celeryproject.org/en/latest/contributing.html#reporting-bugs

