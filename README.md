# clarifai-ios-nsfw-detector

In this project, the user uploads an image and receives an NSFW/SFW status with a given likelihood. If the probability of NSFW is greater than 85%, the image is classified as NSFW.

<img src="http://i.imgur.com/Tya2t6r.png" width="200">

For more information about the awesome Clarifai API, check out [developer.clarifai.com](http://developer.clarifai.com/)!

## Building and Running

To build this project, you need [Xcode 7](https://developer.apple.com/xcode/download/) and [CocoaPods](http://cocoapods.org/). To build and run:

1. Install dependencies and generate workspace.
  ```
  pod install
  ```

2. Open the workspace in Xcode
  ```
  open ClarifaiApiDemo.xcworkspace
  ```

3. Go to [developer.clarifai.com/applications](https://developer.clarifai.com/applications), click
   on your application, then copy the "Client ID" and "Client Secret" values (if you don't already
   have an account or application, you'll need to create them first).

   Replace the values of `clarifaiClientID` and `clarifaiClientSecret` in
   [Credentials.swift](ClarifaiApiDemo/Credentials.swift) with the ones you copied.

4. Press the "Play" button in the toolbar to build, install, and run the app.
