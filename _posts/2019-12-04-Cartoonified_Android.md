---
title: Cartoonifier_Android
key: 20191204
tags: Tech.
---
Hi friend! I am Dennis.

This file will teach you how to configure & debug the 'Cartoonifier' project on Android platform.

<!--more-->

### 1.OpenCV Android 

[Official Documents](https://opencv.org/android/)

![Opencv4Android](https://github.com/seuzht/seuzht.github.io/raw/master/Images/opencv4Android.png)

Introduction into AndroidDevelopment
https://docs.opencv.org/2.4/doc/tutorials/introduction/android_binary_package/android_dev_intro.html)

OpenCV4Android SDK
https://docs.opencv.org/2.4/doc/tutorials/introduction/android_binary_package/O4A_SDK.html#o4a-sdk

Android Development with OpenCV
https://docs.opencv.org/2.4/doc/tutorials/introduction/android_binary_package/dev_with_OCV_on_Android.html

### 2.Preparation for Related Software Tools and PlugIns

[JDK](https://www.oracle.com/technetwork/java/javase/downloads/index.html)

Android Dev Environment adt-bundle android-studio sdk adt

[Download](https://blog.csdn.net/u013758456/article/details/51939104)

adt-bundle = Ecipse+(NDK)+Android SDK + ADT +CDT

[NDK Download](https://developer.android.google.cn/ndk/downloads)

[com.android.ide.eclipse.ndk_23.0.2.1259578.jar](https://pan.baidu.com/s/1jHSkCZG?fid=710081727453245) 
let Eclipse "windows-Preference-Android" has "NDK".

[OpenCV-Android-SDK](https://sourceforge.net/projects/opencvlibrary/files/opencv-android/2.4.11/OpenCV-2.4.11-android-sdk.zip/download

### 3.Installation and Configuration

Edit the Android.mk file：

![androidmk] (https://github.com/seuzht/seuzht.github.io/raw/master/Images/androidmk.png)

adt-bundle Installation and Eclipse Configuration

https://jingyan.baidu.com/article/1612d500a83696e20e1eee0b.html

Open Android Project on Eclipse

https://blog.csdn.net/widenstage/article/details/81284679

Eclipse ND Configuration

https://www.cnblogs.com/chenjiajin/archive/2012/04/12/2444188.html

Android NDK: APP_STL stlport_static is no longer supported

https://www.jianshu.com/p/29650d3a5eab （choose right NDK version）

Opencv Configuration on Eclipse

https://blog.csdn.net/colourful_sky/article/details/69487720

[Error:Program "sh" not found in PATH] (https://blog.csdn.net/qingyanyichen/article/details/51153419)

Finally the project catagory tree like this:

![catagorytree](https://github.com/seuzht/seuzht.github.io/raw/master/Images/catagorytree.png)

App Icon like this:
  
![AppIcon](https://github.com/seuzht/seuzht.github.io/raw/master/Images/appIcon.png)

Run it and get the cartoonified image by clicking the screen:

![Example](https://github.com/seuzht/seuzht.github.io/raw/master/Images/effectImage.png)

[Send me email](mailto:zhanghaitao@estun.com) if you have any questions.

If you like it, please don't forget to give me a star :smile:.

[GitHub Pages](https://github.com/orgs/EstunSWRD/teams/wetogo_pc_software) 
