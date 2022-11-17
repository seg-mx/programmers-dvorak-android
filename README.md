# Programmer's Dvorak layout
This is a Android app for adding programmer's dvorak to physical layouts, you only need to install the apk file

___

Tested Android versions:
* 8.1.0

___

## AltGr
The layout includes a basic altgr support:
* `altgr + a` = `á`
* `altgr + e` = `é`
* `altgr + i` = `í`
* `altgr + o` = `ó`
* `altgr + u` = `ú`
* `altgr + n` = `ñ`

(Using shift will insert the letters in uppercase)

# Building
Add a `./local.properties` file:

```
sdk.dir = /path/to/your/android/sdk
```

Then compile using gradle:

```
$ bash gradlew build
```

The apk should be in `./app/build/outputs/apk/debug/` directory
