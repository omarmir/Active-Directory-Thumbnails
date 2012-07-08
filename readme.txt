=== Active Directory Thumbnails ===
Contributors: MirWindsor - Omar
Donate link: 
Tags: authentication, active directory, ldap, authorization, security, windows
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Works with Active Directory Integration to take AD octet string and convert them to images which you can use in themes and anywhere you can use WordPress meta info.

== Description ==

Works alongside Active Directory Integration (http://wordpress.org/extend/plugins/active-directory-integration/)

Uses Active Directory Integration created data from the AD server to create Image files to be saved on the server with their URL accessible via a meta field for use in templates and/or other places depending on your WordPress knowledge.

Example: 

<img src="<?php echo $user->adt_user_photo_url; ?>" class="thumbnail-css" />

== Installation ==


1. Login as an existing user, such as admin.
2. Upload the folder named active-directory-integration to your plugins folder, usually wp-content/plugins.
3. Activate the plugin on the Plugins screen.
4. Configure the plugin via Users >> Active Directory Thumnbnails


== Frequently Asked Questions ==


== Screenshots ==


== Changelog ==

= 0.5 =
* First release

== Upgrade Notice ==

= 1.0 =
Upgrade notices describe the reason a user should upgrade.  No more than 300 characters.

= 0.5 =
This version fixes a security related bug.  Upgrade immediately.