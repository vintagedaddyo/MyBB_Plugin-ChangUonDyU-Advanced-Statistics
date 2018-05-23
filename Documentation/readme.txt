ChangUonDyU - Advanced Statistics 1.0.2
By: ChangUonDyU & updated by Vintagedaddyo

FEATURES:

- Display latest posts in all forum and in specific forums. Auto Refresh using AJAX

- Display Topx: Top posters, newest members, top thanked, most views thread, hottest thread (most reply thread), most popular forum. Choose by Select Menu

- Choose result (by select menu)

Plugin Installation:

- Upload file

    inc/plugins/changstats.php
    inc/languages/english/changstats.lang.php
    inc/languages/english/admin/changstats.lang.php

- Goto admincp > Plugins > active ChangUonDyU - Advanced Statistics 

- Edit index template

Find:

Code:

{$header}

Add below

Code:

<br />	
<script type="text/javascript" src="{$mybb->asset_url}/inc/plugins/changstats/prototype.js?ver=1603"></script>
{$changstats}
<br />


* note: you can choose to move that anywhere in the index page if you want hence why currently no automatic index template edit was included in the plugin.

DONE!!!

Settings Location Instruction:

To change options:

Goto AdminCP > Configuration > Settings > ChangUonDyU - Advanced Statistics


Current localization:

- english
- englishgb
- espanol
- french
- italiano


ChangUonDyU - Advanced Statistics works well with Thanks plugin. You can download the latest version of Thanks (compatible with MyBB 1.8) from the link below:

https://www.dropbox.com/s/29h8arwa34x72pj/Thanks_3.9.2.zip?dl=1
