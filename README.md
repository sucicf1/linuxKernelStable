Built kernel 5.7.8 compatibile with WSL2
Ms default kernel is old and is build with old gcc. I used the Ms WSL2 kernel .config and modified
it to include Kernel Virtual Machine (KVM). I built it with gcc 10.1. Load the kernel in WSL2.