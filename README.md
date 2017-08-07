# VagrantVM

- There is an assumption that you have VirtualBox and Vagrant installed. If you do not, please visit https://www.virtualbox.org/wiki/Downloads & https://www.vagrantup.com/downloads.html respectively to download these.

- Navigate to the directory where you wish to run your virtual environment. Using the shell (terminal / console), run the following commands to bring up the machine with VirtualBox provider and get access to the its shell
```sh
$ vagrant up
$ vagrant ssh
```
- Run the following command to install nginx (engine x). It will prompt you: `Do you want to continue? [Y/n] y`. Type `y`.
```
$ sudo apt-get install nginx
```
- Visit `development.local/`. If you're using Google Chrome, prefix the address with `http://` as Google will recognise it as a search term instead of an address to visit.
