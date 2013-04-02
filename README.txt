This is the play_licensing library from the Android SDK.

Changes from the stock SDK source:

(1) various extraneous imports have been removed

(2) modified to expose whether or not the license 
information was pulled from the server or was from a cache.

The affected file is: 

src/com/google/android/vending/licensing/APKExpansionPolicy.java

The flag is used during start-up to determine whether
to pull data down from the server

