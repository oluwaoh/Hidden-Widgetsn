# Hidden Widgets
This is an iOS 14 app what uses widgets that blend into your wallpaper. It supports all three available widget sizes-small, medium and large.
If you are encountering a bug, please create an issue on this repository. 

## Installation
If you can, you should sideload the IPA provided in the releases section in this repository.  
  
If that doesn't work, you will have to install the app from Xcode. You will need Xcode 12 (currently in beta). Follow the instructions given below to install the app using source.
1. Clone this repository.
2. Open the `.xcodeproj` file from the cloned repository.
3. Click on the topmost parent folder on the left `HomeScreenSpaces` (with a blue `xcodeproj` file icon).
4. Make sure the `HomeScreenSpaces` target is selected on the targets pane on the left.
5. Under the Signing & Capabilities tab, change the team to your account.
5. Change the bundle identifier to have your name/domain name. For example, if your domain name is `abcd`, change the bundle identifier to `com.abcd.homescreenspaces`
6. In the App Groups section (below the signing section), uncheck the existing app group with my domain name. Create a new app group and name it `group.[YOUR_BUNDLE_IDENTIFER]`. For example, if you had set your bundle identifier to `com.abcd.homescreenspaces` in step 5, set the app group name to `group.com.abcd.homescreenspaces`.
7. Make sure you change the bundle identifier's company name for the remaining two targets by selecting them from the targets pane on the left. Also make sure you set the app group of the `EmptySpaceWidgetExtension` target to be the same as the main `HomeScreenSpaces` target.
8. Connect your iOS 14 device and select it from the device selector on the top left.
9. Hit the run button and wait while Xcode installs the app on your device.

## Demo
<div align="center">
   <a href="https://www.youtube.com/watch?v=QpmxEY4o4Iw"><img src="https://img.youtube.com/vi/QpmxEY4o4Iw/0.jpg" alt="DemoT"></a>
 </div>

## Donate
If you enjoy this app and would like to support the developer, please consider donating.  
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/aryanchaubal/)
