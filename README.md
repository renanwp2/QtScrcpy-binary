# QtScrcpy-binary
The binary for [QtScrcpy v 1.7](https://github.com/barry-ran/QtScrcpy) compiled on Debian Buster, which means that this binary works on all Debian-based distros. This repository was created to make your job easier to have the necessary binaries, and not o have an updated version of QtScrcpy. If you stricly need newer versions due to some bug or necessary feature, and not due to a [Shiny New Stuff Syndrome](https://wiki.debian.org/DontBreakDebian#Don.27t_suffer_from_Shiny_New_Stuff_Syndrome), I recommend you to compile QtScrcpy yourself.


To make it work, just git clone this repository: 

`git clone git@github.com:renanwp2/QtScrcpy-binary.git`

If the binary QtScrcpy does not run after becoming an executable, try the command on terinal

`ldd QtScrcpy`

to track any library lacking on your system.
