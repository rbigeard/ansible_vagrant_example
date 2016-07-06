## LAMP Stack automated installation with Ansible ##

This ansible playbook installs a full lampstack on a CentOS box and also installs wordpress

The following ports are mapped to localhost:
Host 8080 -> Guest 80
Host 22   -> Guest 2222

After executing "vagrant up --provision", got to http://localhost:8080/wordpress

Tested with VirtualBox 4 on Ubuntu and Parallels 10 on OS X

If behind a proxy, install the vagrant-proxyconf plugin and configure proxy as needed in the Vagrantfile
