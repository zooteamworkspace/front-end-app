## Front End App based on React Native Firebase Starter<a href="https://github.com/invertase/react-native-firebase-starter"><img align="left" src="https://i.imgur.com/JIyBtKW.png" width="180px"></a>

---

A basic react native app with [`react-native-firebase`](https://github.com/invertase/react-native-firebase) pre-integrated  to get you started quickly.

---


### Getting Started

> This project has been set up for Android system only. Please skip the steps for **[iOS]**

#### 1) Clone & Install Dependencies
**You will need to be running Node version 7.6 or greater for the rename functionality to work**
- 1.1) `git clone this repo`
- 1.2) `cd front-end-app` - cd into your newly created project directory.
- 1.3) Install NPM packages with your package manager of choice - i.e run `yarn` or `npm install`
- 1.4) **[iOS]** `cd ios` and run `pod install` - if you don't have CocoaPods you can follow [these instructions](https://guides.cocoapods.org/using/getting-started.html#getting-started) to install it.
- 1.5) **[Android]** No additional steps for android here.


#### 3) Add `Google Services` files (plist & JSON)

- 3.1) **[iOS]** Follow the `add firebase to your app` instructions [here](https://firebase.google.com/docs/ios/setup#add_firebase_to_your_app) to generate your `GoogleService-Info.plist` file if you haven't done so already - use the package name generated previously as your `iOS bundle ID`.
- 3.2) **[iOS]** Place this file in the `ios/` directory of your project.
  - Once added to the directory, add the file to your Xcode project using 'File > Add Files to "[YOUR APP NAME]"…' and selecting the plist file.

#### 4) Start your app

- 4.1) Start the react native packager, run `yarn run start` or `npm start` from the root of your project.
- 4.2) **[iOS]** Build and run the iOS app, run `npm run ios` or `yarn run ios` from the root of your project. The first build will take some time. This will automatically start up a simulator also for you on a successful build if one wasn't already started.
- 4.3) **[Android]** If you haven't already got an android device attached/emulator running then you'll need to get one running (make sure the emulator is with Google Play / APIs). When ready run `npm run android` or `yarn run android` from the root of your project.

If all has gone well you'll see an initial screen like the one below.

## Screenshots

![preview](https://github.com/zooteamworkspace/front-end-app/blob/master/doc/images/2019-04-20_12-31-36.jpg)
