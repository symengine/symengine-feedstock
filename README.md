About symengine
===============

Home: https://github.com/symengine/symengine

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: SymEngine is a fast symbolic manipulation library, written in C++



Installing symengine
====================

Installing `symengine` from the `symengine` channel can be achieved by adding `symengine` to your channels with:

```
conda config --add channels symengine
```

Once the `symengine` channel has been enabled, `symengine` can be installed with:

```
conda install symengine
```

It is possible to list all of the versions of `symengine` available on your platform with:

```
conda search symengine --channel symengine
```



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/symengine-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/symengine-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/symengine-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/symengine-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/symengine-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/symengine-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/symengine/symengine/badges/version.svg)](https://anaconda.org/symengine/symengine)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/symengine/symengine/badges/downloads.svg)](https://anaconda.org/symengine/symengine)


Updating symengine-feedstock
============================

If you would like to improve the symengine recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`symengine` channel, whereupon the built conda packages will be available for
everybody to install and use from the `symengine` channel.
Note that all branches in the conda-forge/symengine-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
