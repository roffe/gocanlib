# goCANlib

Golang implementation for using Kvaser [CANlib SDK](https://kvaser.com/canlib-webhelp/index.htm) in Windows

You need the drivers for your Kvaser device and the Kvaser CANlib SDK found at [https://kvaser.com/download/](https://kvaser.com/download/)

```
CGO_ENABLED=1
CGO_CFLAGS="-IC:\Path\To\Canlib\INC"
CGO_LDFLAGS="-LC:\Path\To\Canlib\Lib\x64"
```

Example usage in [goCAN Kvaser driver](https://github.com/roffe/gocan/blob/master/adapter/kvaser.go)
