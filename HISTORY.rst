.. :changelog:

History
=======

0.10.0 (2016-04-30)
------------

* Change the default artifact name from the function name to the fully qualified module and function name.
  This will invalidate previously cached artifacts unless the names are migrated or explicitly set.
* Documentation! A start at least, more docstrings and guides will be added soon.
* Adds ``use_cache`` parameter and config option for when you only want to track provenance but not look for cache hits.
* Adds ``check_mutations`` option to prevent ``Artifact`` value mutations.
* Adds ``tags`` parameter to the ``provenance`` decorator for when you only want to track provenance but not look for cache hits.
* Adds experimental (alpha!) ``keras`` support.
* Adds a visualization module, pretty basic and mostly for docs and to illustrate what is possible.
* Adds ``ensure_proxies`` decorator to guard against non ``ArtifactProxy`` being sent to functions.

0.9.4.2 (2016-03-23)
---------------------

* Improved error reporing when paramiko not present for SFTP store.

0.9.4.1 (2016-03-22) (0.9.4 was a bad release)
---------------------

* Adds ability for a database and/or schema to be created when it doesn't exist.
* Adds SFTP blobstore as separate package provenance[sftp].
* Adds examples to illustrate how the library is used.

0.9.3 (2016-02-17)
---------------------

* Patch release to fix packaging problems in 0.9.2.

0.9.2 (2016-02-17)
---------------------

* Adds archive_file feature.

0.9.1 (2015-10-05)
---------------------

* Python versions now supported: 2.7, 3.3, 3.4, 3.5

0.9.0 (2015-10-05)
---------------------

* First release on PyPI. Basic functionality but lacking in docs.
