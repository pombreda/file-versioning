versioning_fs
=============
[![Build Status](http://192.168.11.66/192.168.11.65/travis/versioning_fs/status.svg?branch=master)](http://192.168.11.66/192.168.11.65/travis/versioning_fs)
[![License](https://pypip.in/license/versioning_fs/badge.png)](https://pypi.python.org/pypi/versioning_fs/)

Incremental versioning file system for PyFileSystem using rdiff-backup.


## Installation

    pip install versioning_fs

## Requirements

This library depends on 'rdiff-backup'. On Debian based systems:

    sudo apt-get install rdiff-backup


## Usage
TODO: add some examples

     f = self.fs.open(file_name, 'rb', version=3)