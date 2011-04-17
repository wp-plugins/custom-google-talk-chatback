=== Custom Google Talk Chatback ===
Contributors: MrVictor
Donate link: http://intervaro.se
Tags: google, google talk, google talk chatback, gtalk, jabber, chat, instant message, support, online support, live support, live help, online chat, web chat, live chat, contact, contact form, widget, shortcode, template tag, plugin, links, sidebar
Requires at least: 2.5
Tested up to: 3.1
Stable tag: 1.0

Let's you easily embed Goole Talk Chatback on your site for online chat support. Use the widget, shortcode or template tag.

== Description ==

Lets users on your blog chat with you live through Google Chatback. If you are offline it links to a contact form instead. Works great for live support or live help on your site!

Very customisable

Special thanks to [Israelwebdev](http://israelwebdev.wordpress.com/2009/02/05/google-talk-status-api-in-php) who made the script that makes it possible to check if a user is online or offline.

**The Google Talk Hash Key (ID)**
To use this plugin you first need to know what you hash key is for your Google Talk account. The hash key is the string containing characters and numbers, found between the *tk=* and *&* at http://www.google.com/talk/service/badge/New or for domain users, at: http://www.google.com/talk/service/a/**YOUR-DOMAIN-HERE**/badge/New

Features:
* Custom "start chat link" and "offline text". Use text or image.
* Display things depending on if the user is online or offline
* Widget, Shortcode and Template Tag support

For 

Visit [Intervaro Web Agency](http://wordpress.org/ "Visit Intervaros website") to chat with us about this plugin ;-) or if you want to hire us!

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add the widget, insert shortcode into the WYSIWYG or use template tag in your theme template.

**The Google Talk Hash Key (ID)**
To use this plugin you first need to know what you hash key is for your Google Talk account. The hash key is the string containing characters and numbers, found between the *tk=* and *&* at http://www.google.com/talk/service/badge/New or for domain users, at: http://www.google.com/talk/service/a/**YOUR-DOMAIN-HERE**/badge/New


**Widget instructions**
Just drag the widget to the prefered sidebar and set it up as wanted.

**Shortcode instructions**
There are 3 shortcodes available.

[gtalk hash="" link="" offline=""]
*Prints a link to start chat or a text message if offline*
* Hash: your hash key (ID) for Google Talk Chatback
* Link: link text
* Offline (optional): text if offline

[gtalk_online hash=""] [/gtalk_online]
*Content inside shortcode will only be displayed if user is online*

[gtalk_offline hash=""] [/gtalk_offline]
*Content inside shortcode will only be displayed if user is offline*

**Template Tag instructions**
'<?php gtalk_status( $hash ) ?>'
*Returns 1 (true) if online and 0 (false) if offline*

'<?php gtalk_link( $hash, $link ) ?>'
*Returns a link to start chat*
* Hash: your hash key (ID) for Google Talk Chatback
* Link: link text or image (HTML)

== Frequently Asked Questions ==

None yet..

== Screenshots ==

1. Widget settings

== Changelog ==

== Upgrade Notice ==

== A brief Markdown Example ==

Ordered list:

1. Some feature
1. Another feature
1. Something else about the plugin

Unordered list:

* something
* something else
* third thing

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`
