[English](./README.md) | [한국어](./README.kr.md)
![Cover image](https://user-images.githubusercontent.com/30883319/139041228-f88b6e2f-4523-4d56-913e-927956e88dc6.png)

# Stipop UI SDK for iOS

![Release](https://img.shields.io/github/v/release/stipop-development/stipop-ios-sdk?sort=semver&style=flat&label=release)
![Beta](https://img.shields.io/github/v/release/stipop-development/stipop-ios-sdk?include_prereleases&sort=semver&style=flat&label=beta)
[![SwiftPM compatible](https://img.shields.io/badge/SwiftPM-compatible-green.svg?style=flat)](https://swift.org/package-manager/)
[![CocoaPods compatible](https://img.shields.io/badge/CocoaPods-compatible-green.svg?style=flat)](https://cocoapods.org/pods/Stipop)

Stipop SDK provides over 150,000 .png and .gif stickers that can be easily integrated into mobile app chats, comment sections, live streams, video calls, etc. Bring fun to your mobile app with stickers loved by millions of users worldwide.

## Requirements

- Swift 5.4+
- XCode 12.5+
- iOS 10.0+

## Getting started

- Check [Stipop Docs](https://docs.stipop.io/en/sdk/ios/get-started/quick-start) for the comprehensive guide.

- Sign up to [Stipop Dashboard](https://dashboard.stipop.io/create-application) to download Stipop.plist file.

## Try demo(for XCode 13.0+)

1. Download(or Clone) Demo App
   (SPM or Cocoapods Adjustment is not necessary)

```bash
git clone https://github.com/stipop-development/stipop-ios-sdk
```

2. Add Stipop.plist file into the project

   ![screenshot](https://user-images.githubusercontent.com/30883319/138623975-d5666bad-e0b4-405b-beaf-ed233e376135.png)

3. Run demo app

<p align="center"><img src="https://user-images.githubusercontent.com/30883319/139041399-d4aee7d3-387f-4f9e-a045-f239a0cc2918.png"></p>

## How to install in your project

### Swift Package Manager

#### By XCode

Go to File > Swift Packages > Add Package Dependency...
Enter `https://github.com/stipop-development/stipop-ios-sdk`. Then select a version you want to use.

#### By Package.swift

If you have a Swift Package, add dependency into Package.swift

```swift
dependencies: [
    .package(url: "https://github.com/stipop-development/stipop-ios-sdk.git", .upToNextMajor(from: "0.3.1"))
]
```

### Cocoapods

Copy & Paste below into `Podfile`. Then, run `pod install`.

```ruby
pod 'Stipop'
```

## Contact us

- For more information, visit [Stipop Docs](https://docs.stipop.io/en/sdk/ios/get-started/quick-start).
- Email us at tech-support@stipop.io if you need any help.
