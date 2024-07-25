.. role:: raw-html-m2r(raw)
   :format: html


:raw-html-m2r:`<!-- markdownlint-configure-file { "MD024": false } -->`

Changelog
=========

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog <https://keepachangelog.com/en/1.1.0/>`_\ ,
and this project adheres to `Semantic Versioning <https://semver.org/spec/v2.0.0.html>`_.

[Unreleased]
------------

1.2.0 - 2024-07-20
------------------

Fixed
^^^^^


* Missing dependency on requests

1.1.0 - 2024-07-16
------------------

Changed
^^^^^^^


* use wtforglib for delete_empty_dirs
* use yaml-settings-pydantic for yaml configuration management

1.0.1 - 2024-06-24
------------------

Changed
^^^^^^^


* Only compare archive when not testing in gitlab pipeline.
* Remove publish targets from Makefile

Fixed
^^^^^


* Corrected build project name

1.0.0 - 2024-06-24
------------------


* *First release.*
