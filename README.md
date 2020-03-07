
# react-native-platform-pay

## Getting started

`$ npm install react-native-platform-pay --save`

### Mostly automatic installation

`$ react-native link react-native-platform-pay`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-platform-pay` and add `RNPlatformPay.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNPlatformPay.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNPlatformPayPackage;` to the imports at the top of the file
  - Add `new RNPlatformPayPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-platform-pay'
  	project(':react-native-platform-pay').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-platform-pay/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-platform-pay')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNPlatformPay.sln` in `node_modules/react-native-platform-pay/windows/RNPlatformPay.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Platform.Pay.RNPlatformPay;` to the usings at the top of the file
  - Add `new RNPlatformPayPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNPlatformPay from 'react-native-platform-pay';

// TODO: What to do with the module?
RNPlatformPay;
```
  