# CSE 15L Week 1 Lab Report

Hello! Welcome to CSE 15L. In order to assist in our experience in CSE 12 and 15L, we will learn to use tools such as the `bash` and the terminal, `git` and version control, and IDEs. These tools and shortcuts will help optimize your programming experience throughout your academic and professional career.

I'll walk through downloading an IDE, securely connecting to a remote server with `ssh`, and using some bash commands. For reference, I use a Windows machine running the *Windows Subsystem for Linux (WSL)* and by distribution is *Ubuntu 20.04*. 

### 1. Visual Studio Code
#### Install and Download VS Code
- *Visual Studio Code* is an **Integrated Development Environment** (IDE).
- VS Code essentially acts as a text editor with many advanced features and extensions that assist while writing code.
- Install and download VS Code here for your system: https://code.visualstudio.com/

image x2

- Once downloaded, open any existing folder as a workspace. Alternatively, you can create new directories and files directly in *VS Code*.
#### Open the Terminal
- For our next step, we'll need access to the *terminal* or the *Command Line Interface (CLI)*
- At the top task bar, open the *Terminal* tab, then select *New Terminal*.

image

- A terminal will open at the bottom. Depending on your machine, it may be *Powershell/Windows*, *Mac*, *Linux*. 
- We will be using the `shell`*scripting language*. Some shells:
	- `bash`: "bourne-again shell"
	- `zsh`: zshell

image

### 2: Connect to the Remote Server with ssh 
- `ssh` stands for "secure shell"
- With `ssh` we can securely connect to a remote server and use its terminal as if we are physically on that machine. Our local machine is the *client* and the host is the *server*.
```bash
ssh <hostname@host>
```
- In our case, the *client* is your

### 3. Use the Command Line
- The shell will begin with $
- Once you've logged into your CSE15L account through `ssh` on the `ieng6` server, try some commands.
```shell
rhandran@ieng6$ ls
rhandran@ieng6$ ls -l
rhandran@ieng6$ ls -a
rhandran@ieng6$ cd 
rhandran@ieng6$ 
```
