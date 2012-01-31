# raspberry Pi Devbox

A virtual machine built for raspberry pi development, based on http://russelldavis.org/2012/01/27/setting-up-a-vm-for-raspberry-pi-development-using-virtualbox-scratchbox2-qemu-part-1/ Uses vagrant/puppet to maintain and update the installed software.

## Usage

Install Vagrant 0.9, clone this repository and run "vagrant up". Requires a 64bit machine since this is a 64bit VM. 

## Todo

* all of this is still quite rough
* the path to qemu and scratchbox2 is currently not set up properly, add a 'export PATH="/home/vagrant/raspberry_pi_development/qemu/bin/:/home/vagrant/raspberry_pi_development/scratchbox2/bin:$PATH"' to the .bashrc
* improve on the readme
* add hostonly networking and nfs share
* add a second vm that has X
