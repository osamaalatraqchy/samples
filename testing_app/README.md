# testing_app

A Sample app that shows different types of testing in Flutter.

This particular sample uses the [Provider][] package but any other state management approach
would do.

[provider]: https://pub.dev/packages/provider

This sample is currently being built. Not all testing types are covered yet.

## Goals for this sample

Show how to perform:

- [X] Widget Testing,
- [X] Flutter Driver(Integration) Testing,
- [X] Performance Testing, and
- [X] State Management Testing using the [Provider][] package.

### How to run tests
TODO: Create a mini guide on how to run each testing style.
- Widget Tests:
  - To run on physical device or emulator:
    - Navigate to the project's root folder using command line.
    - Run `flutter run test/<file_path>`
- Flutter Driver Tests:
  - To run on physical device or emulator:
    - Navigate to the project's root folder using command line.
    - Run `flutter drive --target=test_driver/<file_path>`
- Performance Tests:
  - To run on physical device or emulator:
    - Navigate to the project's root folder using command line.
    - Run `flutter drive --target=test_driver/<file_path> --profile` (Using a physical device and running performance tests in profile mode is recommended).
- State Management Tests:  
  - Navigate to the project's root folder using command line.
  - For Unit Testing the provider
    - Run `flutter test test/<file_path>`
  - For Testing State using Flutter Driver
    - Run `flutter drive --target=test_driver/<file_path>`
    
## Questions/issues

If you have a general question about Testing in Flutter, the best places to go are:

- [Flutter documentation](https://flutter.dev/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/flutter)

If you run into an issue with the sample itself, please
[file an issue](https://github.com/flutter/samples/issues).