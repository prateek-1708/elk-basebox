# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  
  config.vm.box = "ubuntu/trusty64"

  config.vm.box_check_update = false

  config.vm.network "forwarded_port", guest: 80, host: 38080, auto_correct: true
  #  config.vm.network "private_network", ip: "192.168.33.10"

  # config.vm.provision "shell", inline: <<-SHELL
  #   sudo apt-get update
  #   sudo apt-get install -y apache2
  # SHELL
end
