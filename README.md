# Apache Custom Server
## Tech stack - apache htttpd , html

### How to setup a custom apache httpd server

* Download the httpd source code from ***[apache](http://mirrors.estointernet.in/apache//httpd/httpd-2.4.41.tar.gz)***
* unzip it and place it in the ***usr/src/apache*** directory(create the directory if doesnt exist)
* Open the ***ap_release.h*** file located in ***include folder***
* Edit **AP_SERVER_BASEPRODUC** header and set it to whatever name you would like
* Edit the ***index.html*** file located in ***htdocs folder*** to suit your needs
* Run the following commands in the httpd-2.4.41 folder to compile and install apache httpd
* 1) ***./configure --prefix=/usr/local/httpd-2.4.41***
* 2) ***make***
* 3) ***sudo make install***
* 4) start the server using ***sudo /apache/bin/apachectl -k start***

### Visit localhost
### You can check the error_log file in logs folder to see your custom version name--
