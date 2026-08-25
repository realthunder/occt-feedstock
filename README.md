About occt-feedstock
====================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/occt-feedstock/blob/main/LICENSE.txt)

Home: https://www.opencascade.com/

Package license: LGPL-2.1-only

Summary: this is the occ (opencascade) CAD-Kernel

Development: http://git.dev.opencascade.org/gitweb/?p=occt.git

Documentation: https://www.opencascade.com/content/documentation

Open Cascade Technology (OCCT), formerly called CAS.CADE
is an open source software development platform for 3D CAD,
CAM, CAE, etc. that is developed and supported by Open Cascade SAS.


Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/conda-forge/occt-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/occt-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-occt-green.svg)](https://anaconda.org/realthunder/occt) | [![Conda Downloads](https://img.shields.io/conda/dn/realthunder/occt.svg)](https://anaconda.org/realthunder/occt) | [![Conda Version](https://img.shields.io/conda/vn/realthunder/occt.svg)](https://anaconda.org/realthunder/occt) | [![Conda Platforms](https://img.shields.io/conda/pn/realthunder/occt.svg)](https://anaconda.org/realthunder/occt) |

Installing occt
===============

Installing `occt` from the `realthunder` channel can be achieved by adding `realthunder` to your channels with:

```
conda config --add channels realthunder
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install occt
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install occt
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add occt
# for installing globally
pixi global install occt
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `occt` available on your platform:

<details>
<summary>With conda</summary>

```
conda search occt --channel realthunder
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search occt --channel realthunder
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search occt --channel realthunder
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search occt --channel realthunder

# List packages depending on `occt`:
mamba repoquery whoneeds occt --channel realthunder

# List dependencies of `occt`:
mamba repoquery depends occt --channel realthunder
```

</details>




Updating occt-feedstock
=======================

If you would like to improve the occt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`realthunder` channel, whereupon the built conda packages will be available for
everybody to install and use from the `realthunder` channel.
Note that all branches in the conda-forge/occt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@adam-urbanczyk](https://github.com/adam-urbanczyk/)
* [@adrianinsaval](https://github.com/adrianinsaval/)
* [@looooo](https://github.com/looooo/)
* [@oursland](https://github.com/oursland/)

