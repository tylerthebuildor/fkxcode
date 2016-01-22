# FK Xcode

**You heard me**

This node CLI tool lets you build, install, and run your React Native iOS apps on the simulator without ever
opening Xcode, because who wants to do that.

## Installation

```
npm install -g fkxcode
```

## Usage

**Navigate to the root of your project folder**

```
fkxcode
# That's it you're done. Now just wait.
```

## Options

**If you don't like the defaults**

```
# Options
-p or --project   default: [name of current directory]
-s or --simulator default: 'iPhone 6'
-t or --tmp       default: '[cd]/ios/tmp'
-b or --bid       default: [gets bundle id from [cd]/ios/[project-name]Tests/Info.plist]
-h or --help      default: null
-v or --version   default: null
```

## To Do

* Test on older versions of react-native
* Add android avd support
* Write tests

## Credits

Adapted this project from https://github.com/pressly/react-native-nurse
which is basically a shell script version of this one. This project ads in some
convenient sanity checks and automates more of the process.
