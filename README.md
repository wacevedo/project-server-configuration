## Project: Linux Server Configuration

IP address : 18.216.229.166
SSH port : 2200

DNS Address: http://ec2-18-216-229-166.us-east-2.compute.amazonaws.com/catalog/

Softwares installed and configurations changes made:
- Update package index and upgrade system packages installed with sudo apt-get update/upgrade
- Changed the SSH port from 22 default to 2200. Made sure to configure the Lightsail firewall to allow it
- Apache and mod_wsgi
    configured to serve a python wsgi application
- PostgreSQL
    created catalog database and created an user
- Installed pip for python
- Flask
- sqlAlchemy