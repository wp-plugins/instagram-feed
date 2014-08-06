=== Instagram Feed ===
Contributors: smashballoon
Tags: Instagram, Instagram feed, Instagram photos, Instagram plugin
Requires at least: 3.0
Tested up to: 3.9.1
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add a beautifully clean, customizable, and responsive Instagram feed to your website

== Description ==

Display the Instagram photo feed of any non-private Instagram account.

= Features =
* Super simple to set up
* Completely responsive and mobile ready
* Display multiple Instagram feeds on the same page or on different pages throughout your site
* Customize the width, height, number of phtos, number of columns, image size, background color, image spacing and more!

Lots more features coming soon!

== Installation ==

1. Install the Instagram plugin either via the WordPress plugin directory, or by uploading the files to your web server (in the `/wp-content/plugins/` directory).
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Navigate to the 'Instagram Feed' settings page to configure your Instagram feed.
4. Use the shortcode `[instagram-feed]` in your page, post or widget to display your photos.
5. You can display multiple Instagram feeds by using shortcode options, for example: `[instagram-feed id=1234567 cols=3 width=50 widthunit=%]`

== Frequently Asked Questions ==

= Can I display multiple Instagram feeds on my site? =

Yep. You can display multiple Instagram feeds by using shortcode options, for example: `[instagram-feed id=1234567 cols=3 width=50 widthunit=%]`.

= How do I find my Instagram Access Token and User ID =

We've made it super easy. Simply click on the big blue button on the Instagram plugins Settings page and log into your Instagram account. The plugin will then retrieve and display both your Access Token and User ID from Instagram.

You can also display photos from other peoples Instagram accounts. To find their Instagram User ID you can use [this tool](http://jelled.com/instagram/lookup-user-id).

= Are there any security issues with using an Access Token on my site? =

Nope. The Access Token used in the plugin is a "read only" token, which means that it could never be used maliciously to manipulate your Instagram account.

== Screenshots ==

1. Display your Instagram photos in multiple columns and with a scrollbar if desired.
2. Customize the number of columns, colors and size of the Instagram feed.
3. An example of two columns with no space between photos.
4. The Instagram Settings page. Super simple to set up and customize.

== Changelog ==

= 1.1 =
* New: Added an option to set the number of photos to be initially displayed
* New: Added an option to show or hide the 'Load More' button
* New: Added 'Step 3' to the Settings page explaining how to display your feed using the [instagram-feed] shortcode
* New: Added a full list of all available shortcode options to help you if customizing multiple feeds

= 1.0.2 =
* Fix: Fixed an issue with the Instagram login URL on the Settings page

= 1.0.1 =
* Fix: Fixed an issue with the 'Load More' button opening an empty browser window in Firefox

= 1.0 =
* Launch!