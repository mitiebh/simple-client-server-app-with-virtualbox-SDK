# About project
Generally, in this case, i'll show you how to write and develope application with virtualbox SKD.<br>
After that, i'll work with virtualbox api's, connection with COM port from win to linux and creating an interface to interact with virtual machine.
### Virtualbox SDK
Oracle VM VirtualBox comes with comprehensive support for third-party developers. The so-called Main API of Oracle VM VirtualBox exposes the entire feature set of the virtualization engine.<br>It is completely documented and available to anyone who wishes to control Oracle VM VirtualBox programmatically.<br>
The Main API is made available to C++ clients through COM on Windows hosts or XPCOM on other hosts. Bridges also exist for SOAP, Java and Python. 
### Download and Install SDK
Here you will find [links](https://www.virtualbox.org/wiki/Downloads) to VirtualBox binaries, SDK and its source code. 
### Configuration
After Download and install the pakage, you can follow these steps to config the virtualbox sdk and it's libraries.<br>
1. First in package directory, go to the installer folder and open your command-line, then type the `python vboxapisetup.py install` command.<br>
Note : this command is for install all the virtualbox api and libraries you need for start the coding. second thing you should attention to it is you must installed 32-bit version of python in your system. 
2. At the end, with the `python -m pip install virtualbox` command, we add the main library of virtualbox to my python language using PyPi.
