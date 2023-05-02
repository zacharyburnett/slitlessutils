# Slitlessutils


## Early Development Software Warning
Slitlessutils is early development software and subject to change. Caution is advised


## Quickstart

To install the development version of this repository, please use:
``
pip install git+https://github.com/spacetelescope/slitlessutils.git
``

Please see [our documentation](https://github.com/spacetelescope/slitlessutils/blob/main/docs/install.rst) for the most up-to-date install instructions.


You also need to download the instrument-specific configuration files. To do this, you can either ask slitlessutils to automatically download them from within python:
``
>>> from slitlessutils.config import download_config_files
>>> download_config_files()
``

or you can manually download the tarfile from https://stsci.app.box.com/s/d7l2frydc58zarfbcq7tkn7gx0qe7o9c and unpack it with `tar -xzvf slitlessutils_config_v1.1.tar.gz`. This will expand the archive into a directory names `slitlessutils_config` - you then need to set the `slitlessutils_config` environment variable to the path of this directory with `export slitlessutils_config=[directory path]`. It will be useful to put this command into your `bash_profile` or equivalent so you don't need to set it every time you start a new session.

[Recurring Errors](notes.md)
