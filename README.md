# Reg-and-Log-System
Registration and Login System
 <br>
 <br>
This is a simple user registration and login system for Unity3D, Xampp, Google Mail for Android Device.
 <br>
 <br>
Software Versions Used:
 <br>
Unity 2020.1.6f1
 <br>
XAMPP for Windows 7.4.10
 <br>
Google Chrome
 <br>
 <br>
# Xampp configuration
Install XAMPP in the path C:\xampp.
 <br>
Create a new folder called register2 in C:\xampp\htdocs\ and
 <br>
put inside the login.php, register.php and verify.php files you find here.
 <br>
 <br>
Replace the php.ini file in the C:\xampp\php\ folder with the php.ini found here.
 <br>
Edit the line:
 <br>
sendmail_from = YOUR ACCOUNT @gmail.com
 <br>
by entering your Google mail address.
 <br>
 <br>
Replace the sendmail.ini file in the C:\xampp\sendmail\ folder with the sendmail.ini found here.
 <br>
Edit the lines:
 <br>
auth_username=YOUR ACCOUNT @gmail.com
 <br>
auth_password = YOUR PASSWORD ACCOUNT
 <br>
with your Google mail data.
 <br>
 <br>
Use the SQL code you find here to create the "accounts" table in the "test" database.
 <br>
The XAMPP configuration is finished.
 # Unity configuration
Create a new project in unity and import the package from Unity Asset Store at this link:
 <br>
 <br>
https://assetstore.unity.com/packages/slug/179864
