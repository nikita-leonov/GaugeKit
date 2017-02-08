[![Version](https://img.shields.io/cocoapods/v/GaugeKit.svg?style=flat)](http://cocoapods.org/pods/GaugeKit)
[![Build Status](https://travis-ci.org/skywinder/GaugeKit.svg)](https://travis-ci.org/skywinder/GaugeKit)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
![language](https://img.shields.io/badge/Language-%20Swift%20-orange.svg)
[![License](https://img.shields.io/cocoapods/l/GaugeKit.svg?style=flat)](http://cocoapods.org/pods/GaugeKit)
[![Platform](https://img.shields.io/cocoapods/p/GaugeKit.svg?style=flat)](http://cocoapods.org/pods/GaugeKit)

<img src="https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/GK.PNG" width="200">

# GaugeKit
##Kit for building custom gauges + easy reproducible Apple's style ring gauges.

<img src="https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/appleFitness.png" width="250">
->
<img src="https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/gauge.gif" width="200">



## Example Usage

Just open `GaugeKit.xcworkspace` and run Example project.

## Installation

### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects.

GaugeKit is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

pod "GaugeKit"
```

### Carthage

To integrate GaugeKit into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "skywinder/GaugeKit" >= 1.0
```


#### Embedded Framework

Add GaugeKit as a [submodule](http://git-scm.com/docs/git-submodule) by opening the Terminal, `cd`-ing into your top-level project directory, and entering the following command:

```bash
$ git submodule add https://github.com/skywinder/GaugeKit.git
```

### Manually

If you prefer not to use either of the aforementioned dependency managers, you can simply add swift files into your project manually.


## Features :sparkles:

- Flexible and high-customizible gauges
- Auto-resized views
- Support `@IBInspectable` & `@IBDesignable`
- Written with vanilla `Swift` flavor :baby_chick:

## Usage :rainbow:

- Put on storyboard `UIView`, and set them class `Gauge` and module `GaugeKit`:

![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/IB_class.png)

- Select type of gauge (property `type` in class or `gaugeTypeInt` for changes directly in Interface builder)

       - case `Circle`
       - case `Left`
       - case `Right`
       - case `Line`

##Example:

![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/GaugeKit_sreenshot.png)
![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/SWGauge_example.gif)

###IB Example:

![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/ib_example_1.gif)

## Requirements

- Xcode **8.0** or **later**
- iOS SDK **8.1** or **later**
- **Swift 3.x**  

You can use previous releases if you are looking for support of SDKs starting from **7.0** or Swift starting from **1.2**

## Communication :speaker:

Bug reports, feature requests, patches, well-wishes are always welcome! 

- If you need help, [open an issue](https://github.com/skywinder/GaugeKit/issues/new).
- If you found a bug, [open an issue](https://github.com/skywinder/GaugeKit/issues/new).
- If you have a feature request, [open an issue](https://github.com/skywinder/GaugeKit/issues/new).
- If you want to contribute, see [Contributing](https://github.com/skywinder/GaugeKit#contributing-octocat) section.

## Contributing :octocat:
I'd love to see your ideas for improving this library.

The best way to contribute is by submitting a pull request.

## License

GaugeKit is available under the MIT license. See the LICENSE file for more info.
