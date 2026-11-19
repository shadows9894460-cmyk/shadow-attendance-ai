# SHADOW ATTENDANCE AI

Android Studio project for a standalone attendance reminder and manual attendance tracker.

## Features
- Daily 11:00 AM reminder, intended Monday-Saturday (Sunday reminders are skipped).
- Present / Absent buttons and local attendance history.
- Test voice alert using Android Text-to-Speech. Available voices and gender depend on the phone's installed TTS engine; select a female voice in Android Text-to-speech settings if one is offered.
- Reminder notification channel and reboot rescheduling.

## Build
1. Open this folder in Android Studio (Giraffe or newer; AGP 8.7.3).
2. Allow Gradle sync and install Android SDK 35 if prompted.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Install the generated APK on your Android phone and allow notifications.

## Important limitations
This is a starter app, not an AI connection to the college attendance portal. It does not log in to another app or submit attendance automatically. Attendance is recorded only when the user taps Present or Absent. Android may defer inexact alarms due to battery optimization; verify notification permissions and battery settings.
