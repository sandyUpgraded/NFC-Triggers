NFC-Triggers
============

PURPOSE: 
Use NFC to deep link into an associated native Android application.

SETUP:
Host intent.php on a web server (http://example.com/intent.php) with custom app-specific scheme and syntax 
Tie NFC tag to web address (http://example.com/intent.php) using Tagstand Writer or other NFC web address authoring kit
Install native Android app on phone/tablet. Customize acceptance of parameters.
Navigate browser to http://example.com/intent.php and that should launch the app with custom actions based on parameters.

FILES:
Web folder has PHP code (intent.php) that will redirect a Android Chrome browser to native app.
Native app has settings that will accept the URL with associated parameters.


NOTE: 
*Requires appcompat_v7 project in Eclipse

