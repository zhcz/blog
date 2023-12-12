---
title: >-
  Xcode更新到14.3之后报错，提示‘File not
  found’Applications...lib/arc/libarclite_iphoneos.a
tags:
  - 文章
  - iOS
categories: iOS
hidden: false
abbrlink: 62953
date: 2023-04-10 16:55:04
---

Xcode更新到14.3之后，运行项目报错：
File not found: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/arc/libarclite_iphoneos.a
![](https://picogo-1257295947.cos.ap-beijing.myqcloud.com/iOS/%E6%88%AA%E5%B1%8F2023-04-10%2016.46.56-thumb.png)

解决方案：
修改一下报错的target的版本号
![](https://picogo-1257295947.cos.ap-beijing.myqcloud.com/iOS/%E6%88%AA%E5%B1%8F2023-04-10%2016.56.11-thumb.png)