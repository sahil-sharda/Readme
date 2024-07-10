<a id="readme-top"></a>
<!--
*** Radha Soami Greetings
*** Thanks for checking out the Setup for DCIMS.
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="#">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Setup for DCIMS</h3>
</div>

<!-- GETTING STARTED -->
## Getting Started

Please follow the below steps to setup DCIMS:

1. Install xampp-win32-7.2.5-0-VC15-installer from https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/7.2.5/
2. Install Mysql Workbench https://dev.mysql.com/downloads/workbench/
3. From xampp control panel, start Apache server and Mysql server.
4. connect to the localhost:8080 server with root username and empty password.
5. Go to Administration -> Management -> Data Import ->Import from Self-Contained file -> 'dcims_back_28_May_2024.sql' -> 		select target schema as 'rssb_dcims' -> Go to Schemas and refresh to see the tables.
6. Update the users credential from the file: <<user.sql>> -(Get from Rahul Sharma).
7. Install Git.
8. clone from repo https://github.com/rssbdcims/DCIMS under the following location as:- 'C:\xampp\htdocs\dcims'.
9. Install VSCode or any editor of your choice.
10. Open C:\xampp\htdocs\dcims\frontend\config\bootstrap.php and update the below or database properties:
 
	a. define('DB_DATABASE', 'rssb_dcims');
	b. Place the below files in common/config, frontend/config and console/config:
	c. <<params-local.php>> - (Get from Rahul Sharma).
	d. <<main-local.php>> - (Get from Rahul Sharma).
11. Open the following on the browser: http://localhost/dcims/frontend/web/loging, 
12. the application should open.
13. -Login using '8882321898' and 'QWERTY456'.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Rahul Sharma -

<p align="right">(<a href="#readme-top">back to top</a>)</p>
