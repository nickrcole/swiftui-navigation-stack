# swiftui-navigation-stack Changelog

## 1.1.0
- Presenting the entire view stack to the user to expose partial dismiss animations elegantly.

## 1.0.6
- Fixed a bug that caused a wrong transition animation on iOS 16.

## 1.0.5
- Renamed `NavigationStack` to `NavigationStackCompat` to avoid conflicts with the iOS 16 `NavigationStack` by Apple.
- You can now check whether the NavigationStackCompat already contains a specific view.

## 1.0.4
- Code cleaning.
- Improved documentation.
- NavigationStack has now a depth property.
- Added MacOS and WatchOS deployment target to Podspec.

## 1.0.3
- Fixed Package.swift: the watchOS platform was missing.
