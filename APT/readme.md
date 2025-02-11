## Part 1: Understanding APT & System Updates
1. The APT Version of my system is apt 2.7.14 (amd64) 
![](img/A1.png)
2. Then I updated the package list. It is very important becuase it helps to access latest versions of software , fix the security problem, improve system stability and so on.
![](img/A2.png)
3. Then I Upgrade installed packages. The main difference between update and upgrade is that update command used for refresh the local data package and see if latest version is availabe. And upgrade command used for install that latest version.
![](img/A3.png)
4. Then I view pending updates. There are no pending updates.
![](img/A4.png)
## Part 2: Installing & Managing Packages 
5. There are so many image editor package. So i picked sigil.
![](img/A5.png)
6. sigil require some image processing library such as libhunspell-dev, libjs-jquery-scrollto etc.
![](img/A6.png)
7. Then i install the sigil package. It is successfully installed. 
![](img/A7.png)
8. sigil  2.0.1+dfsg1-1build4 amd64 version installed.
![](img/A8.png)
## Part 3: Removing & Cleaning Packages
9. I run the command for uninstall the package but it was not fully removed.
![](img/A9.png)
10. The main difference between remove and purge is that remove command uninstall the package but not the configuration file but purge comman do both.
![](img/A10.png)
11. Then i remove unnecessary package dependencies. Becuase it will improve my sytem health and also the performance.
12. sudo apt clean command removes cached package files and free some disk space.
## Part 4: Managing Repositories & Troubleshooting
13. After running this command cat /etc/apt/sources.list, there showing that ubuntu sources have been moved and changed the format.
![](img/A11.png)
14. There is Hit 1,2,3,4, package availabe in univers repository.
![](img/A12.png)
15. Then i try to install fakepackage but the system cannot find the package. For this problem first i have to find is there any package availabe called fakepackage. For the i have to run that command apt search fakepackage. Then it will show if there any package name fakepackage and also the deatils of that. 
![](img/A13.png)