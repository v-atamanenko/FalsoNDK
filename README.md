# FalsoNDK (alpha)
FalsoNDK is a library that implements a certain part of Android NDK and enables running Android apps that rely on it (android_main / ANativeActivity-based apps).

Now it is heavily tied to VitaSDK and implements eventfd, pipe, epoll that VitaSDK lacks. In future these things will be abstracted and the library will become possible to use on other platforms as well.

Documentation and usage tutorial is in progress.
