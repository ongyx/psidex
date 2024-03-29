<p align="center">
  <a href="https://github.com/sn3ksoftware/psilib">psilib</a> &bull;
  <a href="https://github.com/sn3ksoftware/psicli">psicli</a> &bull;
  <b> psidex </b>
</p>

# psidex: The Python Script InDEX

![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/sn3ksoftware/psidex?include_prereleases&sort=semver)

(formerly [Pythonista Script Index](https://github.com/ywangd/Pythonista-Script-Index))

<img src="https://raw.githubusercontent.com/sn3ksoftware/psidex/master/psidex_logo.png" alt="psidex_logo:Ψ" width="200"/>

# N.B
This project is not in development anymore. It has been abandoned in favor of [Latte](https://github.com/sn3ksoftware/latte), which is a lot more simpler than the current JSON setup.
You are free to fork and redistribute under the terms of the MIT License if you want.

Welcome to the psidex, a json-based system for python script distribution!
The basis for this came from @ywangd’s [proof of concept](https://github.com/ywangd/Pythonista-Script-Index),
and I decided to try my hand at making a polished, fully working and scalable version.
The package manager used would be [psicli](https://github.com/sn3ksoftware/psicli) (formerly [spkg](https://github.com/sn3ksoftware/sandpkg/tree/testing)), a Python rewrite of the original package manager.

See the [wiki](https://github.com/sn3ksoftware/psidex/wiki) for more documentation.

# Features (as laid out by ywangd in their repo)

* Everything you expect from a normal package manager (install, remove pkgs, etc).
* Info about packages (description, version, author info) stored in json format. This is split into two diffrent files...
   * **package.json**, a file containing detailed infomation about a script/package. Scripts/packages (preferably) each have their own json file, and may share the package.json file (i.e, one per author).
   * **index.json**, a global index file which holds minimal info about **all** scripts/packages available (name, desc., url of package.json). Packages need not be stored in the same server as the index.json file, and may have an external download url (i.e, from another Github repo, etc.)

ywangd's [repo](https://github.com/ywangd/Pythonista-Script-Index) was the original inspiration for all this.
Go check it out if you have the time.

P.S: The pixel-art logo was made by me(!)
You are freely allowed to use the logo as under the same terms of the Python logo creators, in that:

Use of the "two snakes" logo element alone, without the accompanying wordmark is permitted on the same terms as the combined logo.
...
In general, we want the logo to be used as widely as possible to indicate use of Python or suitability for Python. However, please ask first when using a derived version of the logo or when in doubt.
