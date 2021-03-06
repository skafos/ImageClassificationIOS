<h1 align="center">ImageClassificationIOS by <a href="https://skafos.ai">Skafos</a></h1>

ImageClassificationIOS is an example iOS app that uses the Skafos platform for CoreML model integration and delivery. It's a good starting point for diving in, or a good reference for integrating Skafos in to your own app. Skafos is a platform that streamlines CoreML model updates without needing to submit a new version to the app store everytime a new model is ready for use.

This ImageClassification example app specifically integrates and deploys an Image Classification machine learning model. [Image Classification](https://docs.metismachine.io/docs/image-classification) is a type of machine learning model that enables you to categorize images into groups, and identify new images as a member of one (or more) of these groups. The example model that is provided in this app will categorize any image as either a cat or a dog. For more details about how to use and customize this model please navigate to the [Skafos Example Models repo on Github](https://github.com/skafos/colab-example-models).

<br>

## Getting Started

Before diving in to this example application, make sure you have setup an account at [Skafos](https://skafos.ai).

## Project Setup

1. Clone or fork this repository.
2. In the project directory, run `pod install`
3. Open the project workspace (`.xcworkspace`)
4. In your project's settings under `General` change the following:
    * Display Name
    * Bundle Identifier
    * Team
    * Any other settings specific to your app.

## Skafos Framework Setup
Inside `AppDelegate.swift` make sure to set your Skafos **environment keys** in: `Skafos.initialize`. You can find these in your App Settings on the [dashboard](https://dashboard.skafos.ai).

## Now What?

Now take a moment to click on `ImageClassification.mlmodel` and under the *Model Class* section click the arrow next 
to `ImageClassification` and have a peek at the class that Xcode generates from the CoreML Model. Now, inside of 
`MainViewController.swift` take a look at the `viewDidAppear` function to see an example of
how to load a model using the *Skafos* framework.

## License

Skafos swift framework uses the Apache2 license, located in the LICENSE file.

## Questions? Need Help? 

[**Signup for our Slack Channel**](https://skafosai.slack.com/)

[**Find us on Reddit**](https://reddit.com/r/skafos) 

**Contact us by email** <a href="mailto:..">support@skafos.ai</a>
