# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/focal64"


    config.vm.provision "shell", inline: <<-SHELL
     apt-get update
     apt-get install -y apache2
     apt-get install -y php
     apt-get install -y mariadb-server
     apt-get install -y php-mysql
     apt-get install -y libapache2-mod-php
     
   SHELL
end
