# TapashsTestsFramework
# Project Title

Simple overview of use/purpose.

## Description

An in-depth paragraph about your project and overview of use.

## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders
### Requirements
iOS 8.0+ | macOS 10.10+ | tvOS 9.0+ | watchOS 2.0+
Xcode 8
### Integration
# CocoaPods (iOS 8+, OS X 10.9+)
You can use CocoaPods to install SwiftyJSON by adding it to your Podfile:

<!-- platform :ios, '11.0'
use_frameworks!

target 'MyApp' do
    pod 'TapashsTestsFramework', '~> 1.0.0'
end -->

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Tapash Mollick  
ex. [@tapashmpl](https://github.com/tapashmpl)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [TapashsTestsFramework] License - see the LICENSE.md file for details

## Acknowledgments

Code snippets to generate the .xcframework.
xcodebuild archive -scheme TapashsTestsFramework -destination="iOS" -archivePath /tmp/xcf/ios.xcarchive -derivedDataPath /tmp/iphoneos -sdk iphoneos SKIP_INSTALL=NO 


xcodebuild archive -scheme TapashsTestsFramework -destination="iOS Simulator" -archivePath /tmp/xcf/iossimulator.xcarchive -derivedDataPath /tmp/iphoneos -sdk iphonesimulator SKIP_INSTALL=NO


xcodebuild -create-xcframework -framework /tmp/xcf/ios.xcarchive/Products/Library/Frameworks/TapashsTestsFramework.framework -framework /tmp/xcf/iossimulator.xcarchive/Products/Library/Frameworks/TapashsTestsFramework.framework -output TapashsTestsFramework.xcframework
# TapashsTestsFramework
# TapashsTestsFramework

