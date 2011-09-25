Mother
======
This is the build environment for the FreeBSD/nanoBSD installation powering our router, mother.bryggervej.osaa.dk.

More information is available at <http://osaa.dk/wiki/index.php/Mother>

Build Instructions
------------------
1. Install FreeBSD on your build host (tested with FreeBSD 8.x)
2. Install FreeBSD source code in /usr/src (see csup(1))
3. Run '/bin/sh /usr/src/tools/tools/nanobsd/nanobsd.sh -c mother.nanobsd'
4. Have some coffee
5. Upload the new image to mother using upload_nanobsd.sh
6. Enjoy

Files and Directories
---------------------
* **MOTHER.BRYGGERVEJ.OSAA.DK** FreeBSD kernel configuration
* **files** Files to be installed on the image
* **images** Image output directory
* **mother.nanobsd** NanoBSD configuration file
* **packages** Prebuilt FreeBSD ports to be installed on the image
* **upload_nanobsd.sh** Deployment script
