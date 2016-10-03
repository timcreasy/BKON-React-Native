### Quickly Build a Physical Web Application With BKON and React Native

#### Introduction
As software continues to find it's way into our everyday lives, afordable tools such as the BKON A1 make integration with the Physical Web an easy experience.

This guide aims to show how quickly powerful applications can be built utilizing the Physical Web, as the shift towards a mobile world ever increases.

[BKON](https://bkon.com/) is a company based in Nashville, TN., producing hardware and software for the physical web.  [React Native](https://facebook.github.io/react-native/) is a framework to quickly build native mobile applications using React.

#### Requirements
To build a React Native application, the React Native command line interface must be installed.  A getting started guide can be found [here](https://facebook.github.io/react-native/docs/getting-started.html#content).

To use the BKON Mobile SDK, sign up for an account at [PHY.net](https://www.phy.net/).

#### Set Up
For the purposes of this guide, we will narrow our focus to an iOS application with React Native.  Although there are many use cases for beacon technology, a Museum application will demonstrate the interactivity with the BKON SDK.  Our users will have a Museum application, which displays all exhibits nearby, as broadcast by a BKON A1.

Begin by initializing a React Native application using the React Native command line utility (we will be calling this project Museum for here out, but please note this can be a name of your choice):
```bash
react-native init Museum
```

Once the initializes completes, open your project in your favorite editor.  React Native comes with a very useful hot reloading feature, which speeds up application development, allowing reloading of minor changes.  This hot reloading depends on the start script which can be ran by the following commands (leave this running during development):
```bash
cd path/to/Museum
npm start
```

### Building The View
React Native, like React, is a component based framework.  React Native comes with many basic components built in to the react-native module included in every project.  Also, many open-source components are availble, which allow for quick application development.

![](http://i.imgur.com/POa1Ytd.gif)

