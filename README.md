#  ProfileScreenTest
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)

* Standard compliant React Native App Utilizing [Ignite](https://github.com/infinitered/ignite)

## Download Repository

1. `fork` github repo into your account
2. `clone` your fork into desire path
3. `cd` into project directory


#### Additional Steps for iOS Debugging (Recommended for Mac)
1. Install Cocoapods.  Some other software may need to be installed before you can get Cocoapods.  Open terminal to use these commands:
 
 | Software |  Check if installed | Install |
 | --- | --- | --- |
 |Homebrew | `$ brew -v`|  `$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`|
|Ruby | `$ ruby -v` | `$ brew install ruby`|
|Cocoapods | `$ pod --version`| `$ [sudo] gem install cocoapods` |
2. Install Xcode. Open App Store, search for Xcode, and then download the application.

#### Additional Steps for Android Debugging (Recommneded for Windows)
1. Install [Android Studio](https://developer.android.com/studio)

## How to Run App with VSCode

1. Open application with [VSCode](https://code.visualstudio.com/download)
  * If you have never run react-native through VSCode you will also need to download React Native Tools.  Open the Extension Tab ![image](./Docs/Images/Extension-Tab.png) in VSCode and type React Native Tools in the search bar.  Select React Native Tools and then press the install button on the page.
2. Select the Run Tab ![image](./Docs/Images/Run-Tab.png) on the far left
3. Open up the Terminal tab on the bottom panel
4. Install packages with [NPM](https://www.npmjs.com/get-npm) : `npm install` 
  * for iOS:
  	`cd ios; pod install; cd ..`
5. With the Run tab ![image](./Docs/Images/Run-Tab.png) selected, go to the top left of the page and select the debug script. 
  * for iOS: Debug iOS
  * for Android: Debug Android
6. Run application by hitting the play button next to the debug script you just selected.


## Project
Copy this screen to the best of your abilities in the ProfileScreen.js file of the project.

![image](./Docs/Images/Profile-Screen.png)


#### Instructions

1. Componentize anything with a repeatable format.
2. All prop hardcoded values should be defined in mapStateToProps.
3. Actual image/icons are not necessary, but an image/icon should be provided. [React-Native-Vector-Icons](https://github.com/oblador/react-native-vector-icons) library is already included in application.
4. Navigation is not require necessary.  If you don't know how to navigate create an alert that tells where it navigates to instead of preforming the navigation on button press.
5. "Learn More" and "All Activities" buttons should show a view with made up information and then hide the view when the button is pressed again.
6. Bonus Points for adding navigation/animations/redux etc.


## Submission

Once you have completed the project email us your forked github repo url.
