Android Data file browser and .db file fetcher in PHP
=====================================================

I have written this small PHP script which acts a a command line file browser
for android and .db file fetcher. This steals all the Database files which are stored
in the android /data/data folder and the you can inspect it using SQLite Viewer

Usage
=====

`php script.php`

Example Usage
=============

`php script.php`

```
Welcome to .db file extractor !!


List of devices attached

1 emulator-5554

Choose Which device you want to work with? (Enter 1,2,3....)
1

Found Files in the /data/data/ Folder!

1 com.android.contacts
2 com.android.settings
3 com.android.browser
4 com.tictactoe
5 com.android.wallpaper.livepicker
6 com.android.providers.subscribedfeeds
7 com.android.gesture.builder
8 com.example.android.softkeyboard
9 com.example.android.livecubes
10 com.svox.pico
11 com.android.soundrecorder
12 com.android.providers.applications
13 com.android.certinstaller
14 com.android.spare_parts
15 com.android.camera
16 com.android.packageinstaller
17 com.android.sdksetup
18 com.android.providers.drm
19 com.android.htmlviewer
20 com.android.term
21 com.android.customlocale
22 com.android.inputmethod.latin
23 com.android.server.vpn
24 com.android.fallback
25 com.android.development
26 android.tts
27 com.android.globalsearch
28 jp.co.omronsoft.openwnn
29 com.android.gallery
30 com.google.android.providers.enhancedgooglesearch
31 com.android.music
32 com.android.netspeed
33 com.android.calculator2
34 com.android.phone
35 com.example.android.apis
36 com.android.providers.media
37 com.android.mms
38 com.xysecv4
39 com.xysecv3
40 com.android.providers.settings
41 com.android.providers.telephony
42 com.android.providers.contacts
43 com.android.providers.downloads
44 com.android.launcher
45 com.android.alarmclock
46 com.android.email
47 net.learn2develop.SMSMessaging
48 com.android.inputmethod.pinyin
49 com.android.providers.userdictionary
50 com.xysecv5
51 com.activitydemo

Choose Which file you want to get? (Enter 1,2,3....)
Enter R to go back to default directory
Enter e to exit
Enter A to get all .db files from this directory

3

Found Files in the /data/data/com.android.browser/ Folder!

1 app_appcache
2 cache
3 app_geolocation
4 shared_prefs
5 lib
6 app_thumbnails
7 app_icons
8 databases
9 app_databases

Choose Which file you want to get? (Enter 1,2,3....)
Enter R to go back to default directory
Enter e to exit
Enter A to get all .db files from this directory

A
getting all .db files from /data/data/com.android.browser/ directory and beneath it too

.............................32 KB/s (3072 bytes in 0.093s)
53 KB/s (19456 bytes in 0.353s)
27 KB/s (9216 bytes in 0.325s)
50 KB/s (14336 bytes in 0.275s)
54 KB/s (48128 bytes in 0.868s)
3 KB/s (512 bytes in 0.154s)

Found Files in the /data/data/com.android.browser/ Folder!

1 app_appcache
2 cache
3 app_geolocation
4 shared_prefs
5 lib
6 app_thumbnails
7 app_icons
8 databases
9 app_databases

Choose Which file you want to get? (Enter 1,2,3....)
Enter R to go back to default directory
Enter e to exit
Enter A to get all .db files from this directory

e
```

File Structure
==============

- adb-windows.exe  -> adb binary for windows
- adb-linux  -> adb binary for linux
- adb-mac  -> adb binary for mac
- script.php -> the logic and the commandline interface

Author
======

Coded by Subho Halder
- Web: http://subhohalder.com/
- Blog: http://subho.me/

Feel free to contact me !