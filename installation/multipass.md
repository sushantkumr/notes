# Installation
sudo snap install multipass

# Starting a small VM in Ubuntu
multipass launch lts --name ltsInstance --memory 2G --disk 10G --cpus 2

multipass list

multipass stop INSTANCE_NAME
