1. update idea version in file build.gradle and gradle.properties
2. build gradle with follow first command
3. install plugin with local file thrift/build/libs/plugin.jar

[![Build Status](https://api.cirrus-ci.com/github/fkorotkov/intellij-thrift.svg)](https://cirrus-ci.com/github/fkorotkov/intellij-thrift)

Plugin to support Thrift language in IntelliJ

How to build
===============

[JDK 11 or later](https://adoptium.net/) is required to build from source.

```bash
./gradlew :thrift:buildPlugin
```

How to run locally with new changes
===============

```bash
./gradlew :thrift:runIde
```
