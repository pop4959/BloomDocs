---
id: sftp
title: Using SFTP
slug: /sftp
hide_title: true
hide_table_of_contents: false
sidebar_label: Using SFTP For Files
description: This guide will help you use SFTP (MobaXTerm/WinSCP/FileZilla) to transfer files.
keywords:
  - Bloom.host
  - Import Files
  - Export Files
  - Transfer Files
  - SFTP
  - File Access
  - Bloom.host file access
  - Pterodactyl Panel
---
# How to use SFTP to transfer files

### What is SFTP? 
> **S**SH **F**ile **T**ransfer **P**rotocol is one of the most popular methods of securely transferring files to remote servers.


### More Actions
>
> If you wish to archive, unarchive or mass delete files, please check out or [guide](../using_the_panel/file-manager-controls.md) on file management through the panel.


### Using SFTP
> 
> There are several so called *SFTP Clients* few of the more popular ones being [WinSCP](https://winscp.net/), [MobaXTerm](https://mobaxterm.mobatek.net/) or [FileZilla](https://filezilla-project.org/). 
> 
> To find the login details, navigate to the sidebar of the server, then open the 'Settings' section.
> 
> ![sftp](../../static/imgs/using_the_panel/sftp/1.png)
> 

>
> ![sftp](../../static/imgs/using_the_panel/sftp/2.png)
>
> Here you will be able to see your server's SFTP host IP address and port as well as your username! Your SFTP password is the same as your game panel password.
> 
> *With our new panel if you have WinSCP installed, you can launch straight away by clicking `Launch SFTP`.*


---

### Using WinSCP
> Firstly, you'll have to download [WinSCP](https://winscp.net/eng/download.php) to your computer. - This should be simple with their installation wizard.
>
> With our new panel, you can simply head over to the [Duck Panel](https://mc.bloom.host/) and click 'Launch SFTP' under 'Settings' on the left side of the screen. You'll simply need to enter your panel password and you are good to go!
> 

>
> ![sftp](../../static/imgs/using_the_panel/sftp/3.png)
> WinSCP is very similar to your basic Windows Explorer. However, on the right side of the screen (green area) you can see your local files and on the left side (blue area), you can see the remote server's files.
> You can drag, drop, rename and delete files as you wish. 

---

### Using MobaXTerm
> Firstly, you'll have to download [MobaXTerm](https://mobaxterm.mobatek.net/download.html). They do have a free edition and also a professional, paid one. - This should be simple with their installation wizard.
> 
> Once that's done, simply launch the application. Right-click on the left side of the screen and click 'New Session'!
> Here, select 'SFTP' in the middle.
> ![sftp](../../static/imgs/using_the_panel/sftp/4.png) 
> You'll have to enter your host's IP, port and SFTP username (as discussed above). Once that's done, simply click 'Ok'.
> 
> You'll be asked for your panel password. By default, this password will be stored.
>

> ![sftp](../../static/imgs/using_the_panel/sftp/5.png)
> On the left side (green area) of your screen, you can see your local file tree and files and on the left side (blue area) you can see your remote files.
> You can drag, drop, rename and delete files as you wish.

---