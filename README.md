# React Native Environment Config Experiment

Experimentation on managing configuration + automation for React Native projects. The goal is to achieve 12-factor mobile app.

## Things to Experiment:
1. Configuration of environment variables
2. Fastlane integration for iOS and Android (with the store listing)
3. Firebase Environment management
4. CircleCI

## Getting Started

To run in iOS:

```bash
npx react-native run-ios
```

To run in Android, start the emulator from Android studio first, then:

```bash
npx react-native run-android
```

## Useful Commands

Open dev menu in Android:

```bash
adb shell input keyevent 82
```