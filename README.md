# linux-interview-practice
Welcome to the Linux Interview Practice repository! This repository is designed to help you prepare for Linux-related technical interviews by providing a comprehensive collection of interview questions, exercises, and resources.

1. What is Linux?

Ans: Linux is an open source operating system based on the linux kernel. It is mostly used in embedded systems, servers and as a desktop operating system.

2. How is Linux defferent from other operating systems(Like windows or macOS)?

Ans: Linux is an open source, which means its source code is available to the public and anyone can modify and distribute it. Unlike windows or macOS, linux comes in various distros(distributions), each with its package management system and user interface.

3. What is Linux distribution?

Ans: A linux distribution is a collection of linux kernel, system utilities, software packages and a graphical user interface. Each distribution is modified to specific needs and prefernces.

5. What is Linux shell?

Ans: The Linux shell is a command-line interface that allows users to interact with the operating system by typing commands. The most common shell is Bash (Bourne Again SHell), but there are others like Zsh and Fish.

7. How to install Linux on our computer?
  
Ans: 

9. What is sudo?

Ans: SuperUserDo(sudo) is a command which allows a permitted user to execute commands as the superuser or another user, as specified in the sudoers file.It provides a way to perform administrative tasks that require elevated privileges.

10. How can i update and upgrade the system?

Ans: To update the package list and upgrade installed packages, you can use commands like sudo apt update and sudo apt upgrade on Debian-based systems or sudo dnf update on RHEL systems.

11. How do you use remote access tools like SSH to connect to and manage Linux servers?

Ans:To connect to a remote server via SSH, use ssh username@server_ip. Enter the password when prompted. Use scp to securely copy files between local and remote machines.

12. How do you navigate the Linux file system using the command line? 

Ans: To list files in the current directory, we have to use the command "ls". To change directories, use "cd directory_name".For creating new directory, use "mkdir directory_name" and finally to remove a directory, use "rmdir directory_name"

14. Explain how to list files, change directories, and create/remove directories?

Ans: To change directories, use "cd directory_name".For creating new directory, use "mkdir directory_name" and finally to remove a directory, use "rmdir directory_name".

16. How do you create, edit, and manipulate files in Linux using the terminal?

Ans: To create a new empty file, use touch filename. To view the content of a file, use cat filename. To add content to a file, use echo "content" >> filename. To edit a file, use nano filename.

17. What is package management in Linux, and how do you use it to install, update, and remove software?

Ans: Package management is the process of installing, updating, and removing software packages. Different distributions use different package managers, such as apt (Debian-based), dnf (Fedora/RHEL), and pacman (Arch Linux). To install software, use sudo apt install package_name. To update packages, use sudo apt update and sudo apt upgrade.

18. How do we manage users and groups in Linux, including adding, modifying, and deleting them?

Ans:User management commands include useradd to add a new user, usermod to modify user properties, and userdel to delete a user. To manage groups, use groupadd to add a new group, groupmod to modify group properties, and groupdel to delete a group.

19. How do you manage network settings and configurations in Linux?

Ans: Network configurations are typically managed in /etc/network/interfaces or via tools like nmcli or nmtui. Use ifconfig or ip commands to manage network interfaces.

20. What is the Linux firewall, and how do we configure it to control network traffic?

Ans: The Linux firewall is managed by iptables or firewalld (depending on the distribution). Use iptables commands to configure rules (e.g., iptables -A INPUT -p tcp --dport 80 -j ACCEPT).
