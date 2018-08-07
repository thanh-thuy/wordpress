=== Font Awesome Integration ===

Contributors: mcostales84
Donate Link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VWWTUHZWRS4DG
Tags: font awesome, icons
Requires at least: 3.0.1
Tested up to: 4.9.7
Stable tag: 5
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin integrate the Font Awesome library with your wordpress installation.

== Description ==

This plugin just add a simple shortcode to the functions.php file, which embed the latest version of the Font Awesome css (5.1.0). Now using a javascript and the Font Awesome CDN to delivery faster and ligther icons. Now including automatic updates to the icons without even update the plugin!
Once installed, you can go to https://fontawesome.com/icons and check the code of the icon you want to use. Just click on the icon and copy and paste de code wherever you want to use it.

IF you are upgrading from v3 or v4, don't worry, your old shortcodes will continue working ;)

You can also add an icon using the shortcode [fawesome]. This shortcode has four attributes:

- target -> target of the 'a' tag (_blank, _self, _parent, _top)
- href   -> link to use in the 'a' tag
- iclass -> classes to use in the /i/ tag
- aclass -> classes to use in the 'a' tag (deprecated, now you can include your class on the iclass)

** Examples **

[fawesome target="" href="" iclass=""]

[fawesome iclass="fa-cog fa-3x fa-spin"]

[fawesome iclass="fa-facebook" href="http://www.fb.com/jumptoweb" target="_blank"]

NOTE: To see more examples you can use in the iclass parameter, check this page http://fortawesome.github.io/Font-Awesome/examples/

IMPORTANT NOTE: To use the new icons added in v5 of Font Awesome, add the iclass 'fab', Ex. [fawesome iclass="fab fa-amazon-pay"]

== Installation ==

To install this plugin just follow the standard procedure.

or

1. Upload `font-awesome-integration.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Any question? =

Send me an email at mcostales@jumptoweb.com and I will answer you as soon as I can.

== Changelog ==

= 5 =
- Upgrade to version 5.1.0 of Font Awesome. New icons added.

= 4 =
- Upgrade to version 5 of Font Awesome.
- Feel free to upgrade, old shortcodes will continue working.

= 3 =
- Include Font Awesome library as CDN.

= 2.1 =
- Enable the ability to put shorcodes into widgets (in case the theme doesn't permit it).

= 2.0 =
- Add shortcode to display font awesome icons.
- Add the parameters to the shortcode to create a link with custom classes.

= 1.1 =
- Add compatibility with other plugins.
- Add restriction to access the plugin directy.

= 1.0 =
- Just launch the plugin!
