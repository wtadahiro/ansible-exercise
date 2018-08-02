Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.hostname = "ansible-exercise"

  config.vm.network :private_network, ip: "192.168.100.10"
  config.ssh.forward_agent = true
end
