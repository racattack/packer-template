packer-template
================

Quick start
===========

RacAttack packer templates

In order to build a vagrant base box, clone this repo, and review the packer template.

At the moment of this writing, for Oracle Linux, the iso being used is 6.4 that can be downloaded from:

https://wikis.oracle.com/display/oraclelinux/Downloading+Oracle+Linux

The process will validate md5 of the iso, perform a minimal install, and upon reboot will update the critical errata only, install rpm required for racattack, plus epel rpm and ansible.

packer build template.json

[this-project-issues](https://github.com/racattack/packer-templates/issues)

[open issues](https://github.com/racattack/packer-templates/issues?page=1&state=open)

[closed issues](https://github.com/racattack/packer-templates/issues?page=1&state=closed)

[this-project-wiki](https://github.com/racattack/packer-templates/wiki)

[racattack](http://racattack.org)

what is racattack?
======

what is packer?
=======

what can do this for me?
-----------

why this repo?
----------


