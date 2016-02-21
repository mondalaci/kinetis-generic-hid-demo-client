# Kinetis generic HID demo JavaScript client

This is a minimalistic JavaScript client to test whether the generic HID demo of the [KSDK](http://www.nxp.com/products/software-and-tools/run-time-software/kinetis-software-and-tools/development-platforms-with-mbed/software-development-kit-for-kinetis-mcus:KINETIS-SDK) echoes back the sent payload.

Intall node, npm, then `npm install` in order to install the libusb node binding.

Then simply execute `client.js` or type `node client.js` on Windows. You may have to run it as root.

You should see the following:

```
Sending "abcdefgh"
Received "abcdefgh"
```
