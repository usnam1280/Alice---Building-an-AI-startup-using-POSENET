## Overview

[![AUR license](https://img.shields.io/aur/license/pac.svg)](https://github.com/soumyadip1995/Alice---Building-an-AI-startup-using-POSENET/blob/master/LICENSE)
[![Made with flutter](https://img.shields.io/badge/Made%20with-flutter-blue.svg)](https://flutter.dev/docs/get-started/install)

![alt_text](https://miro.medium.com/max/1016/1*2Uw46_A3mLOp21eLruhQuA.png)

In this Repository, We look at how one can build  an automated workout instructor. I have built a workout start up called Alice using flutter and the POSENET model as its base functionality that charges 10 US dollars and can be used by you to build a profitable start up. I I have used posenet model on top of Siraj Raval's Code. Download the tensorflow posenet model as a tflite file from [here](https://www.tensorflow.org/lite/models/pose_estimation/overview). It has also been included in the assets as well(Multi-person tflite file).

- Read my [Blog post](https://soumyadip1995.blogspot.com/2019/07/alice-building-ai-start-up-using.html) to know more about how to build the app and the theory behind the scenes.

## Credits

- Siraj Raval for the video. Healthcare startup
- Shaqian GitHub for the base App [here](https://github.com/shaqian/flutter_realtime_detection)
- Smellslikeml for the Yoganet- GitHub [here](https://github.com/smellslikeml/YogAI)

## Dependencies

All of these can be downloaded in a single command, see below. 

- PoseNet Model 
- Tensorflow Lite
- Stripe
- RazorPay
- Flutter Text to Speech

## Instructions

First install [Flutter](https://flutter.dev/docs/get-started/install). 

After download, from command line run this to install the dependencies
```
flutter packages get
```
Then run this command to run the app

```
flutter run
```
Alternatively you can open the app as a new flutter project in Android Studio after installing the Flutter plugin. 

## Demo
![alt_text](https://github.com/soumyadip1995/Alice---Building-an-AI-startup-using-POSENET/blob/master/figures/Screenshot%20(225).png)

**Note:- This is no way fully complete. This is done, just to show you an idea of how you can get started with flutter and integrate  ML models and create a valuable service with it.**

## How to Improve the app

- Generative Model for 3D Yoga Pose Generation (Adversarial Network)

- More interactive dialogue (Dialogflow)

- More personalization & poses (add more poses, personalize them using recommender system/matrix factorization)

- Other features for well-being (meditation, diet, other forms of exercise)

- More analytics (blood pressure, posture, etc.)
