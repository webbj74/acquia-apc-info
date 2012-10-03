acquia-apc-info
===============

Acquia Cloud's Ubuntu 8.04 webservers are Running APC 3.0.19

For full source code, please see:
* http://svn.php.net/viewvc/pecl/apc/tags/RELEASE_3_0_19/

Due to Acquia's FastCGI implementation a couple of changes need to be made
to apc.php in order APC's password protection to work correctly. The included
file apc-3.0.19.php includes this patch and works with the included .htaccess


The acquia-apc-info folder should be added to "docroot/sites/all/libraries/"
in an Acquia-hosted Drupal repository.

It is highly recommended that you edit the php file and change the username
and password.
