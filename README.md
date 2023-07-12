# sqli-labs-php7-master


SQL Lab: https://drive.google.com/drive/folders/1tiK5J5_1J-ANhAFdEEVgbIGjb3OnLEit?usp=sharing

# Hacking/Bug-bunting practice Free LAb
https://hackxpert.com/labs/

Windows Browser Artifacts Cheat Sheet

# Microsoft Edge (Chromium-based)
User Profile:
%LocalAppData%\Microsoft\Edge\User Data\[Default|Profile X]\*
History (SQLite Database):
%LocalAppData%\Microsoft\Edge\User Data\[Default|Profile X]\History
Cookies (SQLite Database):
%LocalAppData%\Microsoft\Edge\User Data\[Default|Profile X]\Network\Cookies
Cache:
%LocalAppData%\Microsoft\Edge\User Data\[Default|Profile X]\Cache\*
Sessions:
%LocalAppData%\Microsoft\Edge\User Data\[Default|Profile X]\Sessions\*
Settings and Other Configuration:
%LocalAppData%\Microsoft\Edge\User Data\[Default|Profile X]\Preferences

# Google Chrome
User Profile:
%LocalAppData%\Google\Chrome\User Data\Default\*
History (SQLite Database):
%LocalAppData%\Google\Chrome\User Data\Default\History
Cookies (SQLite Database):
%LocalAppData%\Google\Chrome\User Data\Default\Network\Cookies
Cache:
%LocalAppData%\Google\Chrome\User Data\Default\Cache\*
Sessions:
%LocalAppData%\Google\Chrome\User Data\Default\Sessions\*
Settings and Other Configuration:
%LocalAppData%\Google\Chrome\User Data\Default\Preferences



# Mozilla Firefox
User Profile:
%AppData%\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\*
History, Bookmarks, and Downloads (SQLite Database):
%AppData%\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\places.sqlite
Cookies (SQLite Database):
%AppData%\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\cookies.sqlite
Cache:
%LocalAppData%\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\cache2\*
Sessions:
%AppData%\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\sessionstorebackups\*
Settings and Other Configuration:
%AppData%\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\prefs.js


# Microsoft Edge
User Profile:
%LocalAppData%\Packages\Microsoft.MicrosoftEdge_XXX\AC
History, Cookies, and Downloads (ESE Database):
%LocalAppData%\Microsoft\Windows\WebCache\WebCacheV01.dat
Note that local file access will also appear within WebCacheV01.dat. Look for entries similar to:
file:///X:/path/to/file, where “X” is the drive letter on which the file was accessed.
Cache:
%LocalAppData%\Packages\Microsoft.MicrosoftEdge_XXX\AC#!XXX\MicrosoftEdge\Cache
Sessions:
%LocalAppData%\Packages\Microsoft.MicrosoftEdge_XXX\AC\MicrosoftEdge\User\Default
\Recovery\Active
Settings and Other Configuration:
%LocalAppData%\Packages\Microsoft.MicrosoftEdge_XXX\AC\MicrosoftEdge\User\Default
\DataStore\Data\nouser1\XXX\DBStore\spartan.edb

# Microsoft Internet Explorer
Location of Most Artifacts (ESE Database):
%LocalAppData%\Microsoft\Windows\WebCache\WebCacheV01.dat
Sessions:
%LocalAppData%\Microsoft\Internet Explorer\Recovery\*.dat

Copyright by https://www.13cubed.com/downloads/windows_browser_artifacts_cheat_sheet.pdf



