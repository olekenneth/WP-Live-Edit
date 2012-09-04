=== Live Edit ===
Contributors: olekenneth
Donate link: http://olekenneth.com/
Tags: admin, edit, editor, live, wysiwyg, update, save
Requires at least: 2.6
Tested up to: 3.4.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Live Edit is Wordpress plugin that enable the user to update the content, live, on the blog.

== Description ==

Live Edit is Wordpress plugin that enable the user to update the content, live, on the blog. Don't waste time going back and forth between the admin panel and the site. Just update the content emediently while reading the blog post. The plugin is using WPs strict user control access before enabling this feature, so only the users allow to edit the blog post can do it.

== Installation ==

1. Upload `live-edit`-folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to Settings -> `Live Edit
4. Set up which field title and content is showed in on the site. Use jQuery selector: (.entry-title, #post-title, etc).

== Frequently Asked Questions ==

= How do I find out which field the title or content is? =

You need to inspect the title- or content-field. If you use Firebug, right click on the title and click Inspect with Firebug. Look for ...class="entry-title" or ...id="post-title". If you identify by class use the . (dot) else if you use id use the # (hashtag).

= Does it only work with Twenty Eleven? =

No. But for other themes you need to specify which fields is the title and content. See the question over.

== Screenshots ==

1. Settings panel.
2. Live edit in action.

== Changelog ==

= 0.0.1 =
* Added basic functionality.

== Upgrade Notice ==

= 0.0.1 =
* Just install :-)