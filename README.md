# ApacheBasics
This repo will explain the basics of apache for Beginners
 	
## Installing Apache:
	
		rpm -q httpd
		rpm -qa | grep -i httpd
		yum install httpd
		yum install httpd-devel
		yum install mod_perl
		yum install php php-mysql
		yum install openssl mod_ssl

# To Query the Database
rpm -q httpd

# Query all the DB and check if httpd package is installed
rpm -qa | grep -i http

# Install Apache Web Server
yum install httpd 

# Check to see if Apache is installed if successful you should get a version number
rpm -q httpd

# Check to see if HTTPD is installed a dependency called httpd-tools is installed
rpm -qa | grep -i http

# Install an Apache supported package
yum install mod_packagename
