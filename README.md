About git
=========

Home: https://git-scm.com/

Package license: GPL-2.0-or-later and LGPL-2.1-or-later

Feedstock license: [BSD-3-Clause](https://github.com/sdvillal/git-feedstock/blob/master/LICENSE.txt)

Summary: distributed version control system

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/git-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/git-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-git-green.svg)](https://anaconda.org/sdvillal/git) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/git.svg)](https://anaconda.org/sdvillal/git) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/git.svg)](https://anaconda.org/sdvillal/git) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/git.svg)](https://anaconda.org/sdvillal/git) |

Installing git
==============

Installing `git` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
conda config --set channel_priority strict
```

Once the `sdvillal` channel has been enabled, `git` can be installed with:

```
conda install git
```

It is possible to list all of the versions of `git` available on your platform with:

```
conda search git --channel sdvillal
```




Updating git-feedstock
======================

If you would like to improve the git recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/git-feedstock are
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

* [@sdvillal](https://github.com/sdvillal/)

