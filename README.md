[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/2.0.0/active.svg)](https://github.com/xoopscube/xcl)
![License GPL](https://img.shields.io/badge/License-GPL-green)
![License GPL](https://img.shields.io/badge/X--Update%20Store-Pending-red)

## ///// — Xpress : multiple WordPress blogs

This repository is currently only used for issue tracking for 

- Xpress
- XCpress

    NOTE : Stale branch version = 5.7.5  
    Wordpress later versions have a Fatal error: Maximum function nesting level of ‘256’ reached  
    and users on shared hosting cannot change the setting xdebug.max_nesting_level to a higher value to fix it.  
    Disable XDebug or find how to get out of the loop then.


MODULE | Xpress
------------ | -------------
Description |  XCL installation and management of multiple WordPress blogs.
Render Engine | Smarty v2 and XCube Layout
Version | 5.7.5
Author | Toemon 
Author | Update by Nuno Luciano (aka Gigamaster) XCL PHP7
Copyright | 2005-2022 Authors
License | GPL


##### :computer: The Minimum Requirements



          Apache, Nginx, etc. PHP 7.2.x
          MySQL 5.6, MariaDB  InnoDB utf8 / utf8mb4
          XCL version 2.3.+



-----

          
          
Xpress
=======
Xpress Integration Kit is a module to run and manage multiple WordPress blogs.    
Sync users, groups and roles, customize blocks, smarty tags, wrap WordPress  
into XCL default theme.      

## Environment

XOOPS Cube Legacy 2.2 or later XCL 2.3.x

## Main Features

* Create WordPress blogs
* Sync User groups and roles
* Member rank (guest/associate/regular/staff/owner)
* Member management by group staffs
* Permission policy management by group owner
* Add group image (requires LEImg module)

## /////////////////////// — Usage

XCL installer wizard (GUI).

## /////////////////////// — Settings

- Module Setttings  
- Blocks 
- Theme 
- Templates

## /////////////////////// — License

License GPL


## Update History

0.21.1 (2021.03.15) gigamaster  

* Add XCLayout Helper
* Fix Xpress default theme
* Fix deprecated functions
* Fix Notice and Warning
* SQL varchar from 255 to 191  
* Fix Cube XCL  
  [WIP]...
