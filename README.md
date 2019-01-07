# Devops-Interview-Questions
Devops Interview Questions

## Software Delivery
### What is Continuous Integration?
It is the part of software development strategies where fresh code commits are integrated and code is tested with the changes.Many of the developers are working on different part of coding of project. They may working on some functions which are later has to be integrated and tested accordingly. While this module is integrated with some of the branch,(respected to some branch ) it needs to be tested that they are working correctly with other modules of project. This integration has to be tested to make sure that this code modules works correctly with other module. The process of combining code modules with fresh changes to the main module is called as continuous Integration.It is very usefull for early bug discovery and bug fixes.By integrating regularly we can detect errors quickly and discovers them easily.

### What CI tools have you used?
As there are so many CI tools are available in market and each has their own advantages and limitations. The most popular CI tool nowdays and I have used is, jenkins. It is open source Integration Server that comes with numbers of plugins and huge community support.With the helps of plugins , its can able to provide many features. and with it's community support , we can find solution of any problem that we are facing while working with Jenkins.


## Linux
### How can you view running processes?
We can use ```top``` command for that. ```htop``` we can use for interactive process viewer.

### How do you check server uptime?
By using ```uptime``` command. by providing -p option, it will show the output in pretty format.

### How do you start/stop services?
To start or stop service , we can use service command with sudo option.
##### To start the services , we can use
```
sudo service <service-name> start
```
##### To stop the services, we can use
```
sudo service <service-name> stop
```

### How do you display the shell’s environment variables?
We can simply use ```printenv``` command for this.

### What does #!/bin/bash at the top of a script do?
The ```#!``` symbol call as Shebang. Shebang acts as an interpreter to execute the file(script file.).Like if we added #!/bin/bash then the interpreter shell here is bash shell. and all commands or the instructions specified in the script are executed by the bash shell.
### What does "&" after a command do?
Whenever we want to run the command or a script in background , then at last of command we use "&". It will use when some script or some command take much time for execution so that we don't need to wait for its execution or at the time when we don't want to loose shell prompt and want to continue with it.

### What does piping commands mean?
The piping ```|``` mean providing output of one command to the input to another command. Like if we want to check whether the particular user is available in the system we can first print the /etc/passwd file using ```cat``` and provide the output of this to ```grep``` to search the particular String in it. Like as follows
```
cat /etc/passwd | grep "sunrays"
```
The above command will result like
```
sunrays:x:1002:1002::/home/sunrays:
```
Otherwise it will be empty.

### What distributions have you used on servers?Why?
I have used Ubuntu and CentOS on servers. These are the mostly used distributions on cloud because of its Support , Ease of use, and Simplicity. These Distributions are open source and free to use. Both distributions has large community support and it's easy to learn.

## Configuration Management
### Which Configuration Management tools are you most comfortable with?
Ansible.
