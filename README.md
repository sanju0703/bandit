# bandit
# Bandit Level 0 → Level 1

## Level Goal
The objective of this level is to log into the Bandit game server using SSH.  
The server details are as follows:

- **Host:** bandit.labs.overthewire.org  
- **Port:** 2220  
- **Username:** bandit0  
- **Password:** bandit0  

## Solution

To connect to the server, use the following SSH command:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220


<img width="980" height="215" alt="image" src="https://github.com/user-attachments/assets/ff52590b-cc51-40b1-a7cc-939fbcc4c1cd" />

# Bandit Level 1 → Level 2

## Level Goal
The password for the next level is stored in a file named `-` located in the home directory.  
After retrieving the password, use it to log into `bandit2` via SSH on port **2220**.

## Solution

First, log into the Bandit server as `bandit1` using the password obtained from Level 0.

Once logged in, list the files in the home directory:

```bash
ls


