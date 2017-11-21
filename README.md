# Twilio Access Manager for iOS

This repository contains releases for the Twilio Access Manager for iOS helper.  These releases can be used on their own or the following line in your Cartfile:

    github "twilio/twilio-accessmanager-ios"

Please note that additional steps are required for successful integration of this helper into your project.  Minimally, you must execute a script file during your build process to thin the helper to only the architecture types you are building.  This is necessary before submission to the AppStore.  This script is located in the delivered .framework file, named `remove_archs`.

Please see the [documentation](https://www.twilio.com/docs/api/chat/sdks#carthage-integration "Twilio Access Manager for iOS") located on Twilio's website for more information.
