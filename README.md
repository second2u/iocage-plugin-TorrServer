# iocage-plugin-TorrServer

### plugin to install TorrServer v126 on TrueNAS CORE

https://github.com/YouROK/TorrServer

## install

Download the plugin manifest file to your local file system.

```
fetch https://raw.githubusercontent.com/second2u/iocage-plugin-TorrServer/main/torr-server.json
```

Install the plugin. Adjust the network settings as needed.

```
iocage fetch -P torr-server.json -n TorrServer
```
