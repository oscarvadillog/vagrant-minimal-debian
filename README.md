# vagrant-minimal-debian

`vagrant-asterisk-debian` is a simple vagrant project that simplifies the provision of a minimal Debian OS machine. It can be useful if you want to prepare this kind of scenario quickly.

## Components:
* Vagrant Box: `debian/jessie64`

## Requirements:
* `VirtualBox 5.0.*`
* `Vagrant 1.8.*`

## Usage:
Install `vagrant-vbguest` plugin. It installs the host's VirtualBox Guest Additions on the guest system.
```bash
vagrant plugin install vagrant-vbguest
```

Create and configure the machine:
```bash
vagrant up
```

## License
MIT
