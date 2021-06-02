# Debianization for the Intel I40E Driver

The repository contains so called DEBIAN directory containing the scripts and configs files needed to package the
[Intel I40E driver]() server into a DEB package for a Debian distro.

Waiting for a debian mantainer to adopt this package, this repository will rely on the original
binary distribution of the Intel I40E and later versions.

Using this repository, you will be able to have an Intel I40E driver debian package fully working for easy deploys into your clusters.

## Short DEB-packaging HowTo

1. Simply run the following script included in the repository

```deb-automate-build.sh```

## Installing the Intel I40E driver debian packages

After the build is completed, it's as simple as:

```dpkg -i ../i40e_*_all.deb``` (replace the proper .deb file as the version may have changed)
