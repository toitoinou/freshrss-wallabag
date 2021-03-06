# FreshRSS Wallabag Button

This [FreshRSS](https://freshrss.org) adds a button to each article
which adds the respective article to your
[Wallabag](https://wallabag.it) installation.

FreshRSS already comes with a pretty good integration with Wallabag
through its share feature. The author of this plugin was annoyed by the
fact that the share feature is just a simple link, which means that a
new tab opens when a article is added to Wallabag. This extension uses
the Wallabag API and sends the request from the server side. This means
that your workflow of skipping through articles is not interrupted when
you add an article to Wallabag.

This extension is only compatible with Wallabag v2.

## Setup

1. Copy this extension folder to `extensions` folder of your FreshRSS
   installation
1. In Wallabag, visit *API clients management* and click *Create a new
   client*
1. Choose a name for your application and click create. A client ID and
   a client secret is displayed. You will need these values later.
1. In FreshRSS, go to the settings page and click *Extensions*.
1. A new extension named *WallabagAPI* should be displayed. Click
   *Manage*.
1. Copy and paste the client ID and the client secret from Wallabag to
   FreshRSS. Also fill the URI (for example: `https://app.wallabag.it`)
   and your Wallabag username and password.


## License 

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Note that this license does not apply to embedded libraries, namely the
following files:
* static/jquerymin.js, License: 
  <https://github.com/jquery/jquery/blob/master/LICENSE.txt>
