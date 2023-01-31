MongoDB Packer Challenge

In this task, I crafted a Packer.JSON file with configurations for constructing an Amazon Machine Image (AMI) on Amazon Web Services (AWS). Afterwards, I launched an AWS instance which enabled me to access the virtual machine (VM) using Secure Shell (SSH). Once inside the VM, to confirm that everything was in order, you can see that we run the command 'mongosh' to confirm that it has installed on the virtual machine.

The first video shows 
- running the packer.json configuration file
- You can see it building in the terminal

![Recording](/media-vids/1.gif)

In between the two videos our AMI and instance have been deployed
- The aws AMI built
- From this we configure our instance on AWS

The second video shows 
- The instance being lauched & connected
- I then ssh'd into the machine & you will see that mongdb has been installed onto the VM.

![Recording](/media-vids/2.gif)