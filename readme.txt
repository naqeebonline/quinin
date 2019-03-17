Readme

1)	Create empty database  “ quinine_test  ”
2)	Import Database which is located in DB/ folder.
3)	Download the project  and Run composer update command
4)	Default user is created with 
		username: naqeebonline@gmail.com
		password: 12345678
5)	Create your own user. User email verification will be done from https://mailtrap.io/
Create account in mailtrap.io and make a login to mailtrap. It will give you username and password. Set these information in  .env file. You can also use my test mailtrap account.
  

MAIL_DRIVER=smtp
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=8de17b18e58fee   
MAIL_PASSWORD=8acb2c930b0be3
MAIL_ENCRYPTION=tls

Email verification will be done from here.

6)For automation testing(Laravel Dusk) run command
php artisan dusk


Note: project directory name must be “ quinine_test ”. because that name is used in laravel dusk. If you gives different name . then follow the following directory path
  tests/Browser/ExampleTest.php. on line number 22 update the directory name.

Create Virtual host or access the project by using the following link
http://localhost/quinine_test/public/






