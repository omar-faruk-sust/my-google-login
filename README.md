# my-google-login
This  is sample web application to login with google.
you need to create DB for this project and import the sql file google_login_db.
now run `composer install`
create a php file name with config.php and make an class like this

```<?php
/**
* confil class to set the google client id and secret id
*/
class Config
{
	const CLIENT_ID = '******** here is your google app id',
			CLIENT_SECRET = 'your google secretid';
}
?>```

setup your vhost in local. So that you can browse like me "http://my-google-login.dev".

To know how to get your CLient ID and Secret ID please see the google documentation.
