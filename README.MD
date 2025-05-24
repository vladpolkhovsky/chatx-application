# ChatX Application

To build components, you need Java 17

## Components

1. [chatx-ktor-server](chatx-ktor-server) (need to be installed first)
2. [chatx-android-app](chatx-android-app) (check build instruction, and install Android SDK)

## Installation commands

```
cd chatx-ktor-server
./gradlew clean publishKtorChatDtoPublicationToMavenLocal
cd ..
cd chatx-android-app
./gradlew clean build
cd app/build/outputs
ls -d 2 **.apk
```