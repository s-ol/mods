# `mods` Community Edition

Just like `mods`, but cooler :sunglasses:

![](mods.png)


<!-- vim-markdown-toc GFM -->

* [What is `mods`?](#what-is-mods)
* [Installation](#installation)
* [Setting persistent permissions in Linux](#setting-persistent-permissions-in-linux)
* [Using `mods`](#using-mods)
* [Current status](#current-status)

<!-- vim-markdown-toc -->

## What is `mods`?

`mods` community edition is a fork of [CBA mods research project](https://gitlab.cba.mit.edu/pub/mods). `mods` is a modular cross platform tool for fablabs. It is based on independent but interrelated modules. `mods` could potentially be used for CAD, CAM, machine control, automation, building UI, read input devices, react to to physical models, and much more. The possibilies are endless.

The goal of the community edition is to provide documentation, support and help the community engage in the project and foster the development/exchange of new modules.

## Installation

- Step 1: Clone the `mods` repository: `git clone https://github.com/fabfoundation/mods.git`
- Step 2: Run the installation script `bash install-mods` inside the `mods` folder

Logout or reboot for the permission changes to take effect.

## Using `mods`

- Run `bash start-servers` inside the `mods` directory.

## Documentation and tutorials

Check out the [wiki](https://github.com/fabfoundation/mods/wiki) for a set of guides and tutorials.

## Current status

|                 |  Windows 10 WSL Ubuntu 18 LTS | Ubuntu 18 LTS | Arch Linux |
|-----------------|-------------------------------|---------------|------------|
| Installation    | PASS                          | PASS          | PASS       |
| Running         | PASS                          | PASS          | PASS       |
| Moving machines | SERIAL AND PRINTERS (?)       | ALL           | ALL        |


