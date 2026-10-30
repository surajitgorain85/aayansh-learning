AAYANSH LEARNING - ANDROID APP PROJECT
======================================

This is a ready-to-build Android Studio project. The learning app (index.html)
is bundled inside, so it works fully offline on the device.

HOW TO GET THE APK (about 10 minutes, one time)
-----------------------------------------------
1. Install Android Studio (free): https://developer.android.com/studio
   (If Gradle complains about Java 25, this project already uses Gradle 9.6 and Android plugin 9.4 which support it.)
2. Unzip this folder. In Android Studio choose File > Open and pick the
   "aayansh-android" folder. Wait for "Gradle sync" to finish (first time
   downloads tools, needs internet).
3. Menu: Build > Build Bundle(s) / APK(s) > Build APK(s)
4. When it finishes, click "locate" in the popup. The file is:
   app/build/outputs/apk/debug/app-debug.apk
5. Copy app-debug.apk to the phone/tablet (Google Drive, USB or WhatsApp),
   tap it, allow "Install from this source", and install.

TO UPDATE THE APP LATER
-----------------------
Replace app/src/main/assets/index.html with the newer HTML file (keep the
name index.html) and build the APK again.

NOTES
-----
- Voice uses the phone's built-in text-to-speech. Make sure "Speech Services
  by Google" is installed and media volume is turned up.
- The app opens in portrait and keeps the screen on while in use.
