# Smile
Emoji in Swift

[![CI Status](http://img.shields.io/travis/onmyway133/Smile.svg?style=flat)](https://travis-ci.org/onmyway133/Smile)
[![Version](https://img.shields.io/cocoapods/v/Smile.svg?style=flat)](http://cocoadocs.org/docsets/Smile)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/Smile.svg?style=flat)](http://cocoadocs.org/docsets/Smile)
[![Platform](https://img.shields.io/cocoapods/p/Smile.svg?style=flat)](http://cocoadocs.org/docsets/Smile)

![](Screenshots/Banner.png)

## Features

#### List all emojis

```swift
Smile.list()
```

#### Show standard name of an emoji

```swift
Smile.standardName("🇳🇴") // ["REGIONAL INDICATOR SYMBOL LETTER N", "REGIONAL INDICATOR SYMBOL LETTER O"])
```

#### Search emoji by keywords

```swift
Smile.search(["GRINNING"]) // 😁, 😸
```

#### Search emoji flag by country code

```swift
Smile.flag("no") // 🇳🇴
```

#### Search emoji by alias

Emoji data is from https://github.com/github/gemoji/blob/master/db/emoji.json

```swift
Smile.emoji("japanese_castle" // 🏯
```

## Installation

**Smile** is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'Smile'
```

**Smile** is also available through [Carthage](https://github.com/Carthage/Carthage).
To install just write into your Cartfile:

```ruby
github "onmyway133/Smile"
```

## Author

Khoa Pham, onmyway133@gmail.com

## Contributing

We would love you to contribute to **Smile**, check the [CONTRIBUTING](https://github.com/onmyway133/Smile/blob/master/CONTRIBUTING.md) file for more info.

## License

**Smile** is available under the MIT license. See the [LICENSE](https://github.com/onmyway133/Smile/blob/master/LICENSE.md) file for more info.
