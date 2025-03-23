# BASH Scripting Lab – Compiling Software from Source Code: ProFTPD

## Objective

The main objective of the Linux Lab is to learn how to manually compile and install software from its source code on a Linux system, using ProFTPD (a popular and flexible FTP server) as the example.

### Job Skills Learned

- Understanding the Source Compilation Process
- Installing Required Dependencies
- Customizing Software Installations
- Troubleshooting Common Issues
- Managing Installed Software


### Tools Used

- Linux Terminal Command Line Interface (CLI)
- Package Manager: apt, yum or dnf
- Build Tools: GCC, Make
- Networking Tools: wget, netstat, ss and lsof, ping, ifconfig
- File Management Tools: tar, vim
- VMware Tools: Linux VM
- ProFTPD (a popular and flexible FTP server)



### STEPS


1. Install the prerequisites: gcc, g++, make
Ubuntu: `sudo apt update && sudo apt install build-essential` CentOS: `sudo dnf group install "Development Tools"`
![image](https://github.com/user-attachments/assets/2e2f672f-d85e-40ff-9138-25727dfbd5b6)
![image](https://github.com/user-attachments/assets/ad388899-b561-458e-a6e1-14cd7d29eeb7)
![image](https://github.com/user-attachments/assets/a5f57c3e-15bb-4d1b-8d8a-181a64da9af1)
![image](https://github.com/user-attachments/assets/b5ed2d8a-a790-4954-828f-1d12a51e31db)
![image](https://github.com/user-attachments/assets/6ce905e2-d044-4ab7-ab99-5be537444e59)
![image](https://github.com/user-attachments/assets/32b7df6f-3f81-4e88-bd48-3daf962e73df)


2. Download the source files from the official Website
![image](https://github.com/user-attachments/assets/c620e214-725d-45b8-8069-90568de36e31)
![image](https://github.com/user-attachments/assets/98a73a89-802b-4697-93e6-9d3619009efd)
![image](https://github.com/user-attachments/assets/de23d774-5ee0-48e5-b146-b7d53719a2ba)
 
 
3. Check the integrity of the tarball (hash or digital signature)
![image](https://github.com/user-attachments/assets/0b51edff-f20f-4dbb-98a5-ea1d6488774c)
 

4. Extract the archive and move into the resulting directory
![image](https://github.com/user-attachments/assets/41102e65-c598-4119-864d-2a2d9a4d22ac)
![image](https://github.com/user-attachments/assets/8db4fc64-6233-4395-ace2-89e4b841d6e9)
![image](https://github.com/user-attachments/assets/07d68f02-d118-47ce-a3de-2163d4f05874)
 
 
 


5. Run: `./configure --help` and set the required compilation options
![image](https://github.com/user-attachments/assets/91612817-0771-440c-9a71-fe01cee1d703)
![image](https://github.com/user-attachments/assets/ae473af0-ed58-4a15-960c-fe5b3969d807)
![image](https://github.com/user-attachments/assets/4321da7b-210f-4852-9a49-844c85c87bb7)
![image](https://github.com/user-attachments/assets/fd82b736-c350-497d-8487-7cd17c88ab9b)
 


6. Run: `make`
![image](https://github.com/user-attachments/assets/702407db-cca6-4b05-a36c-d4414dfd3eed)
 

7. Run: make install
![image](https://github.com/user-attachments/assets/21fd889f-3298-4616-a8d3-44310f7200ee)
![image](https://github.com/user-attachments/assets/4d9fe97e-dead-41f6-8561-ba1bf2cada46)
![image](https://github.com/user-attachments/assets/ae1f943c-a5b3-4c06-85b6-d81cf0e4acaa)
![image](https://github.com/user-attachments/assets/f4ca07c7-8314-459c-8023-f48c7203285d)
![image](https://github.com/user-attachments/assets/fcb8d053-e142-4579-ba9f-cb440bae8cbe)
![image](https://github.com/user-attachments/assets/68ee38e4-76f8-47e4-9ed8-83028075c365)
 
 
NMAP port scan results.
![image](https://github.com/user-attachments/assets/93927eaf-d7aa-4057-8391-8aa36f19f3a3)
![image](https://github.com/user-attachments/assets/e59651e4-76ab-436c-9743-301972c21f1c)
 
 
