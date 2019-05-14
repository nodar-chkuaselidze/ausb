Build and dependencies
===

This is a vendored project of two libraries in one:
  - [node-usb][node-usb] (npm: usb) - Node.JS library for communicating with USB devices in
  JavaScript.
  - [webusb][webusb] (npm: webusb) - Node.js implementation of the WebUSB Specification.

webusb dependencies:  
  - WebUSB is using and wrapping [node-usb][node-usb].

node-usb dependencies:  
  - It is an addon and wrapper around [libusb][libusb], but is using custom [fork][libusb-fork].

#### TODO
  - check and try updating from [fork][libusb-fork] to [a latest version][libusb-gh].

[node-usb]: https://github.com/tessel/node-usb
[webusb]:  https://github.com/thegecko/webusb
[libusb]: http://libusb.info/
[libusb-gh]: https://github.com/libusb/libusb
[libusb-fork]: https://github.com/kevinmehall/libusb
