# Apache HTTP server on Arch Linux


![Apache HTTP Project](https://httpd.apache.org/images/httpd_logo_wide_new.png)



## Installation 
1. Open your terminal.
2. Update your system. `sudo pacman -Syu`
3. Install Apache. `sudo pacman -S apache`
4. Uncomment *#LoadModule unique_id_module modules/mod_unique_id.so* in  **/etc/httpd/conf/httpd.conf** file and save changes.

## Basic commands
Command | Action
-|-
`systemctl status httpd.service` | Status
 `systemctl start httpd.service`| Start the server
 `systemctl stop httpd.service` | Stop the server 
`systemctl restart httpd.service`| Restart the server
`systemctl enable httpd.service` | Enable Apache to start at boot
`systemctl disable httpd.service` | Disable Apache to start at boot



By default the root directory is **/srv/http**

More about [Apache HTTP Server](https://wiki.archlinux.org/index.php/Apache_HTTP_Server)
