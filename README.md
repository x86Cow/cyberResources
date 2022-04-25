# Cyber Course

## Guided Curriculum

## Linux

* Installing a distro
  * For the purposes of the beginning segment of this course we will be using a distribution called [**Ubuntu**](https://ubuntu.com/). Ubuntu is a easy to install distribution that can handle all of the basic tasks we will do in the beginning.
  * Ubuntu is derived from another Linux distribution known as **Debian**. This means that it will use the APT package manager (We will get into this later on).
  * Eventually we will move onto Kali Linux; Kali is similar to Ubuntu, but comes pre-installed with tools focused on hacking. This will be our distribution of choice later on after covering fundamental topics.

* Understanding Linux Bash Shell
  * Usage of Linux is very different than Windows. Linux, when used properly, can be the most powerful operating system you will ever use. Understanding the *terminal* (also sometimes refered to as the *command line*, or *shell*) will be the fastest & most productive way of doing things on Linux.
  * *Bash* is the default, commonly-used terminal in Linux, and is what we will be focusing on during this course.

## Explaining Linux

* Linux by itself is not a full operating system. Individuals and groups of people create operating systems.
* Operating systems powered by the Linux kernal are extremely decentralized.
  * In general, Linux is broken down into a hierachy of operating systems; the two primary parent distributions are: **Arch**-based, and **Debian**-based.
    * The above distributions utilize two different package managers: **Aptitude**, for Debian (abbreviated as *APT*), and **Pacman**, for Arch.
    * Unlike Windows, rather than downloading programs as executables from websites via a web browser like Chrome or Edge, you instead install software via your distribution's Package Manager. Package managers install programs, delete programs, and manage dependency requirements for your programs.

## Living In The Terminal

* Editing text with is typically done in Linux with either the built-in, default editor known as *nano*, or with more experience, popular vi type editors.
  * vi type editors are very effective because the mouse is not needed - it is controlled solely with the keyboard.
  * vi is a modal editor; it uses three modes: Normal, Insert and Visual. These modes also allow you to save keybinds (shortcuts) for commonly-used actions.

  * File management
    * **Ranger** is the CLI file manger that I go-to by default. It uses **vi** keybindings, and is very reliable to do anything you need to do. With a fresh installation, it typically takes a bit of time to configure, but once it is configured to your liking it works very well.

### Bash Scripting

* In Bash (and all other Linux shells) you can easily create scripts to automate whatever is needed.
* Scripting is using various command line tools in order to make what you want.
* Pipe
  * The pipe is a very quick and easy way to send the output of a command to the input of the next
* Cron
  * Cron is a time based method of running scripts. Say every day at midnight you want to check for updates, cron is how you do so (I do this by the way).

### Python Scripting

### Web Exploitation

* Password Cracking
* File Upload
* SQL Injection
* Command Injection
* Cross Site Scripting (XSS)

## Cyber Team Resources

* Linux
  * [Unix Toolbox](http://devdoc.net/linux/UnixToolbox.html "Unix Toolbox")
  * [Over The Wire](https://overthewire.org/wargames "Over The Wire (Bandit)")
* Vim
  * [Primeagen Vim Tutorial](https://www.youtube.com/watch?v=H3o4l4GVLW0 "Primagen Vim Tutorial Series")
  * [Luke Smith Vim Tutorial](https://www.youtube.com/watch?v=d8XtNXutVto&t "Luke Smith VimTutor Walkthrough")
  * [OpenVim Tutorial](https://www.openvim.com/ "OpenVim")
  * [Vim Adventures](https://vim-adventures.com/ "Vim Adventures")
* Web Exploitation
  * [Damn Vulnerable Web Application](https://dvwa.co.uk "DVWA")
  * [Web Exploitation CTF101](https://ctf101.org/web-exploitation/overview "CTF101")
