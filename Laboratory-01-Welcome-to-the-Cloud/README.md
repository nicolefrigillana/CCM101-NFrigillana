# Laboratory 01 — Welcome to the Cloud

## Mission Overview
This mission introduces the cloud computing environment using KillerCoda, a browser-based Linux playground. It covers basic Linux navigation, user creation, system information gathering, file organization, and setting up a professional GitHub portfolio repository.

## Objectives
- ✅ Access and use a cloud-based Linux environment
- ✅ Create and manage users with proper permissions
- ✅ Gather and record system information
- ✅ Organize files and directories using Linux commands
- ✅ Build a GitHub portfolio repository
- ✅ Document work using Markdown format

## Activities Performed
1. Launched Ubuntu 24.04 playground on KillerCoda
2. Created new user `nfrigillana` with bash shell, home directory, and sudo access
3. Logged in as new user and recorded username, working directory, and hostname
4. Checked Linux distribution, kernel version, CPU info, total memory, and disk space
5. Created folder structure including `Notes/` and wrote `about-me.md`
6. Created GitHub portfolio repository and organized files properly

## Linux Commands Used
```bash
whoami                  # Display current username
pwd                     # Show current working directory
hostname                # Show system hostname
useradd -m -s /bin/bash -G sudo  # Create user with home, shell, sudo
passwd                  # Set password for user
su - [username]         # Switch to new user account
lsb_release -a          # Check Linux distribution & version
uname -r                # Check kernel version
lscpu                   # Display CPU information
free -h                 # Show memory usage in human-readable format
df -h                   # Show disk space usage
mkdir -p                # Create directories and parent folders
nano                    # Text editor to create/edit files
cat                     # Display contents of a file
ls -la                  # List all files including hidden ones
