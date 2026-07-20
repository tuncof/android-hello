# Android Hello World

A basic, compilable Android Hello World application.

## Prerequisites

- Android Studio (or Android SDK Tools)
- JDK 8 or higher
- Android SDK API level 34

## How to Build

### Option 1: Using Android Studio

1. Clone this repository
2. Open the project in Android Studio
3. Wait for Gradle to sync
4. Click **Build** → **Build Bundle(s)/APK(s)** → **Build APK(s)**
5. The APK will be generated in `app/build/outputs/apk/debug/`

### Option 2: Using Gradle CLI

```bash
# Build debug APK
./gradlew assembleDebug

# Build release APK
./gradlew assembleRelease

# Install on connected device/emulator
./gradlew installDebug
```

## Project Structure

```
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── AndroidManifest.xml
│   │       ├── java/com/example/helloworld/
│   │       │   └── MainActivity.kt
│   │       └── res/
│   │           ├── layout/
│   │           │   └── activity_main.xml
│   │           └── values/
│   │               ├── strings.xml
│   │               ├── colors.xml
│   │               └── themes.xml
│   └── build.gradle.kts
├── build.gradle.kts
├── settings.gradle.kts
└── gradle.properties
```

## Generated APK Location

After building, your APK will be at:
- **Debug**: `app/build/outputs/apk/debug/app-debug.apk`
- **Release**: `app/build/outputs/apk/release/app-release.apk`

## Features

- ✅ Fully compilable Android project
- ✅ Kotlin language support
- ✅ AndroidX libraries
- ✅ Material Design theme
- ✅ Simple Hello World UI
- ✅ Ready to customize

Happy coding!
