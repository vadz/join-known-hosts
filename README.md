Join Entries in SSH Known Hosts File
====================================

This simple script joins all entries using the same key in ssh known hosts
file by putting all hosts using this key on the same line.

Usage:

```console
$ join-known-hosts > new_known_hosts
... examine the new file to confirm that it contains only expected changes ...
$ mv new_known_hosts ~/.ssh/known_hosts
```

Requirements:

- Unix-like system with Perl.
