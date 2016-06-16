-- SUMMARY --

This simple module creates a new block that will display the current system
date/time in a user-defined format.


-- REQUIREMENTS --

This module requires the the Date module to be installed found at
https://drupal.org/project/date.


-- INSTALLATION --

Install as usual:
https://drupal.org/documentation/install/modules-themes/modules-7


-- CONFIGURATION --

Once the module is installed, a new block called "Date Block" will be available
on the block listing page found at /admin/structure/block. You can implement
and position the block within your site using the standard block interface.

By default, the date will display in the format: November 18, 2014 (F j, Y).
This format uses standard PHP Date Formatting and can be changed by configuring
the Date Block at /admin/structure/block/manage/date_block/date_block/configure.
More information on PHP date format options can be found at
http://php.net/manual/function.date.php.
