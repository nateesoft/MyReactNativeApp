# Installation react-native with appcenter (MyReactNativeApp)

## 1. command to create react-native

npx react-native init MyReactNativeApp

  Run instructions for Android:
    • Have an Android emulator running (quickest way to get started), or a device connected.
    • cd "/Users/nateesun/Documents/Tutorial/ReactNativeProject/ms-appcenter/MyReactNativeApp" && npx react-native run-android
  
  Run instructions for iOS:
    • cd "/Users/nateesun/Documents/Tutorial/ReactNativeProject/ms-appcenter/MyReactNativeApp" && npx react-native run-ios
    - or -
    • Open MyReactNativeApp/ios/MyReactNativeApp.xcworkspace in Xcode or run "xed -b ios"
    • Hit the Run button
    
  Run instructions for macOS:
    • See https://aka.ms/ReactNativeGuideMacOS for the latest up-to-date instructions.
    

## 2. add git initialization

git init
git add .
git commit -m "first project commit"

## 3. go to github.com

### 3.1 create new repository

git remote add origin https://github.com/nateesoft/MyReactNativeApp.git
git push -u origin main
