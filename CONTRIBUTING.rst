How To Contribute
=================

Every open source project lives from the generous help by contributors that sacrifice their time and ``service_identity`` is no different.

To make participation as pleasant as possible, this project adheres to the `Code of Conduct`_ by the Python Software Foundation.

Here are a few hints and rules to get you started:

- Add yourself to the AUTHORS.rst_ file in an alphabetical fashion.
  Every contribution is valuable and shall be credited.
- If your change is noteworthy, add an entry to the changelog_.
- No contribution is too small; please submit as many fixes for typos and grammar bloopers as you can!
- Don’t *ever* break backward compatibility.
  If it ever *has* to happen for higher reasons, ``service_identity`` will follow the proven procedures_ of the Twisted project.
- *Always* add tests and docs for your code.
  This is a hard rule; patches with missing tests or documentation won’t be merged.
  If a feature is not tested or documented, it doesn’t exist.
- Obey `PEP 8`_ and `PEP 257`_.
- Write `good commit messages`_.
- Ideally, squash_ your commits, i.e. make your pull requests just one commit.

.. note::
   If you have something great but aren’t sure whether it adheres -- or even can adhere -- to the rules above: **please submit a pull request anyway**!

   In the best case, we can mold it into something, in the worst case the pull request gets politely closed.
   There’s absolutely nothing to fear.

Thank you for considering to contribute to ``service_identity``!
If you have any question or concerns, feel free to reach out to me.
I can usually be found on the ``#cryptography-dev`` channel on freenode_.


.. _squash: http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html
.. _`PEP 8`: http://www.python.org/dev/peps/pep-0008/
.. _`PEP 257`: http://www.python.org/dev/peps/pep-0257/
.. _`good commit messages`: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
.. _`Code of Conduct`: https://www.python.org/psf/codeofconduct/
.. _changelog: https://github.com/pyca/service_identity/blob/master/docs/changelog.rst
.. _AUTHORS.rst: https://github.com/pyca/service_identity/blob/master/AUTHORS.rst
.. _procedures: http://twistedmatrix.com/trac/wiki/CompatibilityPolicy
.. _`freenode`: http://freenode.net
