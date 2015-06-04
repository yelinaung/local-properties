local.properties
===============

Generate local.properties file for your android project because copying the existing one takes more time.

Android Studio can add the `local.properties` file automatially once the project is imported but sometimes, I just want to run the gradle wrapper from command line.
This should come in handy in such case.


Installation
------------

If you've done Go development before and your $GOPATH/bin directory is already in your PATH:

```bash
$ go get github.com/yelinaung/local-properties
$ go install github.com/yelinaung/local-properties
```

How to Use
---------

It's as simple as running `local-properties` command.

```bash
$ cd your-android-app-without-local-properties
$ local-properties
```

It will prompt to overwrite if `local.properties` file already exists.

License
-------
MIT
