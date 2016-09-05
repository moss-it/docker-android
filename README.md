Docker image for Android development.

This container is intended for Continuous Delivery of Android applications.

Features
--------

* Oracle Java JDK
* Google Android SDK and tools
* Creates an emulated **Nexus 6** device for testing the intended application

Usage
-----

You need first to download the image from [Docker Hub](https://hub.docker.com/r/moss/android/):

``` bash
docker pull moss/android
```

Then just execute it:

``` bash
docker run --tty --interactive moss/android
```

