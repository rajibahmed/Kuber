## Practice session # 1 


### Local cluster setup with Podman and Kind 

I was trying to play with kubernetes for awhile. The problem was, I was using a Mac. And minikube was bulky 
need a vm driver to create a cluster. My dev machine will not support running virtualBox as it was a office laptop.
Then I like containerization with docker but do not enjoy the fact there is a massive docker engine running on y machine.


### Podman

Is a redhat product suppose fix everything wrong with docker :). It runs by without a server running like docker.
It has almost 100% of docker cli commands support. So I do not have to think too much. It creates a container and then runs your command.
Pretty nice! but take it with a grain of salt.


### Kind
I was tired minikube before. Did not like it that much, could not make it work with Podman. As the vm-driver is experimental 
and only works for version below 2. So I gave up and use Kind. Kind seems to work with podman, as the main cluster is running a docker engine inside the control plane.
Docker inside docker or to correct myself. Docker inside podman. 


It is a sunday fun project. 
