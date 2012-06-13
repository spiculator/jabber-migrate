jabber-migrate
==============

## ABOUT

`jabber-migrate` is a simple tool which allows you to migrate your roster
from one jabber server to another. This is a replacement for another tool
[migrate.sourceforge.net](http://migrate.sourceforge.net/) which did not
work for me.

This can also be used to edit jabber roster as a text file without migrating
it to another server. You can use any scripts or text editors to do the
editing part, while `jabber-migrate` tools does the import/export part.

## REQUIREMENTS

* `perl`
* `Net::Jabber` module

## USAGE

* `jabber-migrate export <JID> <password> [<server>] [<port>] >export.txt`
* (optional) edit `export.txt` file to add or remove some contacts.
* `jabber-migrate import <JID> <password> [<server>] [<port>] <export.txt`
