# ansible-ipfs
Quick and easy playbook for installing an IPFS node/gateway as a service

If you are looking for a way of using Ansible to deploy and manage a cluster of ipfs nodes/gateways meant for pinning and serving content, you might like my other project, [ipfs-kloud](https://github.com/insanity54/ipfs-kloud)


## What it does

* extract and copy pre-built ipfs binary to /usr/local/bin/ipfs
* create ipfs system service (files/ipfs.conf)
* run ipfs service
  * ipfs daemon runs using standard ports 4001, 5001, 8080



## What it does not do

* set up FUSE


## Contributing

Pull requests and new issues are very much appreciated!
