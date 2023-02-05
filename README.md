### ebpf-workspace
Notes on ebpf projects and experiments

###  Useful links
https://github.com/iovisor/

### Start Here
https://github.com/iovisor/bcc/blob/master/docs/tutorial.md

git clone git clone https://github.com/iovisor/bcc.git

### Amazon linux 2 install: https://github.com/iovisor/bcc/blob/master/INSTALL.md#amazon-linux-2---binary
sudo yum update -y
sudo amazon-linux-extras install BCC
sudo rm /usr/bin/python
sudo ln -s $(which python3) /usr/bin/python
PATH=${PATH}:/usr/share/bcc/tools
sudo execsnoop

### Future: Cillium
https://docs.cilium.io/en/stable/gettingstarted/#gs-guide
