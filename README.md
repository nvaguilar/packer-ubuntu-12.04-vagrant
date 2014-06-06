# Packer Template for Ubuntu 12.04 Image with Vagrant

This repository contains a Packer template for building an Ubuntu 12.04 (Precise 64) machine image that is Vagrant-ready.


## Usage

First, [install Packer](http://www.packer.io/intro/getting-started/setup.html).
Then, clone this repository and `cd` into it.

Run the following:

```
$ packer build packer.json
```

At the end of that, you'll have an Ubuntu 12.04 (Precise 64) Vagrant Box ready for your use.

####Credits
This project is built on top of the <https://github.com/mitchellh/packer-ubuntu-12.04-docker> project.