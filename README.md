
# react-native-wd-ios-call-detection

## Getting started

`$ npm install react-native-wd-ios-call-detection --save`

### Mostly automatic installation

`$ react-native link react-native-wd-ios-call-detection`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-wd-ios-call-detection` and add `RNWdIosCallDetection.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNWdIosCallDetection.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNWdIosCallDetectionPackage;` to the imports at the top of the file
  - Add `new RNWdIosCallDetectionPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-wd-ios-call-detection'
  	project(':react-native-wd-ios-call-detection').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-wd-ios-call-detection/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-wd-ios-call-detection')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNWdIosCallDetection.sln` in `node_modules/react-native-wd-ios-call-detection/windows/RNWdIosCallDetection.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Wd.Ios.Call.Detection.RNWdIosCallDetection;` to the usings at the top of the file
  - Add `new RNWdIosCallDetectionPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNWdIosCallDetection from 'react-native-wd-ios-call-detection';

// TODO: What to do with the module?
RNWdIosCallDetection;
```
  