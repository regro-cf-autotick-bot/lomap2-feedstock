About lomap2
============

Home: https://github.com/OpenFreeEnergy/Lomap

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/lomap2-feedstock/blob/main/LICENSE.txt)

Summary: Alchemical mutation scoring map

Development: https://github.com/OpenFreeEnergy/Lomap

Documentation: https://github.com/OpenFreeEnergy/Lomap

Lead optimization mapper (LOMAP) is an automated algorithm to plan efficient
relative free energy calculations between potential ligands within a
substantial of compounds. The original LOMAP code was mainly based
on commercial APIs such as OpenEye and Schrodinger.
The aim of this project is to develop a new version of LOMAP based on
free avalaible APIs such as RDKit offering the scientific community
a free tool to plan in advance binding free energy calculations.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15682&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/lomap2-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-lomap2-green.svg)](https://anaconda.org/conda-forge/lomap2) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/lomap2.svg)](https://anaconda.org/conda-forge/lomap2) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/lomap2.svg)](https://anaconda.org/conda-forge/lomap2) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/lomap2.svg)](https://anaconda.org/conda-forge/lomap2) |

Installing lomap2
=================

Installing `lomap2` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `lomap2` can be installed with:

```
conda install lomap2
```

It is possible to list all of the versions of `lomap2` available on your platform with:

```
conda search lomap2 --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating lomap2-feedstock
=========================

If you would like to improve the lomap2 recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/lomap2-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@IAlibay](https://github.com/IAlibay/)
* [@dwhswenson](https://github.com/dwhswenson/)
* [@mikemhenry](https://github.com/mikemhenry/)
* [@richardjgowers](https://github.com/richardjgowers/)
