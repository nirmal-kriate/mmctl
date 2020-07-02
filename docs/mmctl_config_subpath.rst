.. _mmctl_config_subpath:

mmctl config subpath
--------------------

Update client asset loading to use the configured subpath

Synopsis
~~~~~~~~


Update the hard-coded production client asset paths to take into account Mattermost running on a subpath.

::

  mmctl config subpath [flags]

Examples
~~~~~~~~

::

    config subpath
    config subpath --path /mattermost
    config subpath --path /

Options
~~~~~~~

::

  -h, --help          help for subpath
      --path string   Optional subpath; defaults to value in SiteURL

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --format string                the format of the command output [plain, json] (default "plain")
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --local                        allows communicating with the server through a unix socket
      --strict                       will only run commands if the mmctl version matches the server one

SEE ALSO
~~~~~~~~

* `mmctl config <mmctl_config.rst>`_ 	 - Configuration

