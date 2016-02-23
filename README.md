# kea-contrib
Kea files that are contributed and maintained by the Kea community.

## Info

This repository is a place for storing content contributed by Kea
community that ISC decided to not include in the main Kea repository.

There may be multiple reasons why ISC decides to put a contributed
content here rather than in the main Kea repository. To give two
examples, Linux distribution specific scripts is something that is
similar between distributions, but may vary a bit. Users of distribution
A may prefer the script to look differently than users of distribution
B. Note there is not the right or wrong way here. Nevertheless ISC could
get an endless stream of patches changes the script back and forth and
this is something we'd like to avoid. Also, ISC prefers to work on the
Kea code that could benefit all users, regardless of which OS or
distribution they use.

Second example are patches that ISC has no way of checking or maintaining
on its own. For example, someone could donate a patch that stores
leases in LDAP, which is a reasonable thing to do and some people
may find it useful. ISC does not have a working LDAP setup, so can't
verify if the patch is valid or not. As such we prefer to keep such
changes in the Kea contrib repository rather than in main Kea repo.

## Contributing to this repository

You're more than welcome to send pull requests with your changes. If
you put a new file or a directory, please make sure that you attach
suitable description of what the file does and how to use it. You
may want to also update AUTHORS file.

Unless otherwise noted, the files in this repository are distributed
under Mozilla Public License 2.0 (http://mozilla.org/MPL/2.0/). By
sending a pull request, you agree to release your content under MPL 2.0.
If you want to use a different license, please clearly state so in the
content of your pull request.

## Useful links

If you're interested in the main Kea repository, it is available here:
http://github.com/isc-projects/kea. Kea website is available here:
http://kea.isc.org. If you have a patch and are unsure what to do with
it, the best place to ask is kea-dev:
https://lists.isc.org/mailman/listinfo/kea-dev

Thanks for using and contributing to Kea

Tomek Mrugalski
ISC Kea Software Engineer
