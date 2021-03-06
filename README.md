# Uber Like Cab Service
This project is an Uber like Android app with php backend. It allows you to book the nearest available cab. Driver app is also present in the repo along with the server code.

## Prerequisites
1. Android API key - https://cloud.google.com/docs/authentication/api-keys#api_key_restrictions
2. Google Maps API key - https://developers.google.com/places/android-sdk/get-api-key#restrict-key
3. OneSignal API key - https://documentation.onesignal.com/docs/accounts-and-keys

## STEP 1
```git clone

## STEP 2
1. Open the User App in Android Studio.
2. Put your GOOGLE_MAPS_API_KEY and ANDROID_API_KEY in `strings.xml`.
3. Repeat the same process in Driver App.
4. In Driver App, also replace ONE_SIGNAL_APP_ID in build.gradle (module:app) with your id.

## STEP 3
1. Deploy the php server.
2. Open `database.sql` and update line number 20 i.e.,
```
-- Database: `id11748254_nearcabs`
```
3. Import the `database.sql` file in MySQL.
4. Replace the network call urls in the Android App code with your server url.
