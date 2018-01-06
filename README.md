Roundcube plugin: ForwardAttachment
===================================

This plugin extends the forward as attachment function in the core to allow
forwarding of multiple messages at the same time

forked from JohnDoh/Roundcube-Plugin-Forward-Attachment for historical and older purposes.

Newer version since RC 1.1 already has this implemented.

## Information ##

* RC : 0.8.999 , 0.9.X, 1.0.X
* php: 5.2+
* contextmenu plugin for RC << 1.0.X

This plugin is released under the GNU General Public License Version 3+
(http://www.gnu.org/licenses/gpl.html).

Even if skins might contain some programming work, they are not considered
as a linked part of the plugin and therefore skins DO NOT fall under the
provisions of the GPL license. See the README file located in the core skins
folder for details on the skin license.

### Install ###

* Place this plugin folder into plugins directory of Roundcube as `forwardattachment`
* Add forwardattachment to $rcmail_config['plugins'] in your Roundcube config

todo: How to enable forward message toolbar/contextmenu buttons when select multiple messages.

The Requirements are:
* Specific version of roundcube << 1.1 https://github.com/roundcube/roundcubewemail 
* Specific version of contextmenu plugin https://github.com/roundcubevnz/rc-plugin-contextmenu

