=== Silk AJAX Comments ===
Author: Callum Silcock
Tags: ajax, comments, fix, wordpress, callum, silcock, 2012, new, error, handling, issue, update, commentform, form, comment, simple
Requires at least: 3
Tested up to: 3.4.1
Stable tag: 1.0
Contributors: Callum Silcock
License: GPLv2

The default wordpress comments system is awful when it comes to handling errors, this fixes this issue with some simple AJAX.

== Description ==

Instead of taking you to a different page (wp-comments-post.php) which does not redirect this script just ads some quick text above your form to let your users know if there was an error or if the comment was posted successfully (if successful it then clears the form).

There are a few plugins that do a simliar thing to this already but unfortunately most of the current AJAX commenting solutions I found in the plugin directory havent been updated in years or just didn't work, so following on from many "how to AJAX'ify your wordpress comments" blog posts I thought i'd make a simple plugin instead (which means no coding knowledge required).

The script chooses the #commentform div/form as this is default.

Ill update this plugin when needed but I do not offer any warranty or support for it.

== Installation ==

1. Upload the `silk_ajax_comments` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the `Plugins` menu in WordPress
3. Make sure your comment form has the ID #commentform in your theme (this is default)
4. ?????
5. Profit

== Changelog ==

= 1.0 =
First release

*   Everything works, i've tested accross a few websites, will update if needed.

== Frequently Asked Questions ==

Q: It's not working?
A: Make sure the comment form div has the ID #commentform in your theme