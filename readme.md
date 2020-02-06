### functions.php for phpldapadmin fix: 

PhpLdapAdmin uses a few functions which are deprecated in PHP 7.2. Take a look at this fix: https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=890127

I added the fixes and made a repo so people can just copy/paste

If you find this page first here is a link to the stackoverflow explaining this problem: 
https://stackoverflow.com/questions/50698477/cant-create-new-entry-phpldapadmin


Below is the error and what not. ---- the file is in this repo labeled as functions.php -.- 
```
Deprecated: __autoload() is deprecated, use spl_autoload_register() instead in /usr/share/phpldapadmin/lib/functions.php on line 54

Deprecated: Function create_function() is deprecated in /usr/share/phpldapadmin/lib/functions.php on line 1083
```
