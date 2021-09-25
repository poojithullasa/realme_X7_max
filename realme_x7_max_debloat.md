# Install dev tools in your machine

For Ubuntu:

```sh
    sudo apt install adb
    sudo apt install fastboot
```

# Connecting mobile with PC:

1. Connect PC to mobile via USB-C cable provided in the box
2. Open Terminal and enter the following commands:

```sh
    adb devices
    adb shell
```

## Basic Commands for Uninstall, Install, Enble and Disable app:

```sh
    pm uninstall -k --user 0 com.package_name.com
    cmd package install-existing com.pakcage_name.com
    pm enable com.package_name.com
    pm disable-user com.package_name.com
```

Note: You can find the complete list of package name with apk name with command:

```
pm list packages -f
```

# Debloating the rom

```sh
pm uninstall -k --user 0 com.opos.cs
pm uninstall -k --user 0 com.heytap.browser
pm uninstall -k --user 0 com.coloros.backuprestore
pm uninstall -k --user 0 com.google.android.contacts
pm uninstall -k --user 0 com.heytap.cloud
pm uninstall -k --user 0 com.netflix.partner.activation
pm uninstall -k --user 0 com.netflix.mediaclient
pm uninstall -k --user 0 com.redteamobile.roaming
pm uninstall -k --user 0 com.google.android.youtube
pm uninstall -k --user 0 com.google.android.apps.googleassistant
pm uninstall -k --user 0 com.finshell.fin
pm uninstall -k --user 0 com.google.android.apps.photos
pm uninstall -k --user 0 com.google.android.apps.nbu.paisa.user
pm uninstall -k --user 0 com.facebook.services
pm uninstall -k --user 0 com.facebook.system
pm uninstall -k --user 0 com.facebook.appmanager
pm uninstall -k --user 0 com.google.android.apps.nbu.files
pm uninstall -k --user 0 com.coloros.phonemanager
pm uninstall -k --user 0 com.google.android.apps.maps
pm uninstall -k --user 0 com.google.android.apps.messaging
pm uninstall -k --user 0 com.android.chrome
pm uninstall -k --user 0 com.android.providers.partnerbookmarks
pm uninstall -k --user 0 com.heytap.music
pm uninstall -k --user 0 com.coloros.video
pm uninstall -k --user 0 com.google.android.googlequicksearchbox
pm uninstall -k --user 0 com.google.android.feedback
pm uninstall -k --user 0 com.heytap.themestore
pm uninstall -k --user 0 com.coloros.screenrecorder
pm uninstall -k --user 0 com.coloros.soundrecorder
pm uninstall -k --user 0 com.coloros.weather2
pm uninstall -k --user 0 com.coloros.compass2
pm uninstall -k --user 0 com.coloros.calculator
pm uninstall -k --user 0 com.coloros.alarmclock
```
