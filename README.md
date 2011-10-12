README
======

Building packages
-----------------

It's just a couple of steps

* First, copy packager.ini.orig to packager.ini.
* Next, add in the paths to pyrus and your ZF2 root directory
* Finally, run:

  `php scripts/make-all-packages.php`

* Then:

  `php scripts/release-all-packages.php`

That's it. Then commit to the github repository, and checkout
from the server (where the actual channel is located)
 