# What the Thing ?

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=102)](https://github.com/what_the_thing)  &nbsp;&nbsp;
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/thordenson/what_the_thing)  &nbsp;&nbsp;
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/thordenson/what_the_thing)

Point camera at things to learn how to say them in a different language.

Native Android App built with [React Native](https://github.com/facebook/react-native).

Made it as a part of my learning process of [React](https://github.com/facebook/react-native) and [React Native](https://github.com/facebook/react-native).

Inspired by [Thing Translator](https://github.com/dmotz/thing-translator) by [dmotz](https://github.com/dmotz).

![ezgif-2-c2d47b51b0](https://cloud.githubusercontent.com/assets/14950089/24720723/b2305c4e-1a5b-11e7-8717-672866128ef0.gif)
&nbsp;&nbsp;&nbsp;&nbsp;
![58e4ef22e1d7d646107794](https://cloud.githubusercontent.com/assets/14950089/24707372/ec7b4538-1a30-11e7-944d-98addd4ff146.gif)


![](https://oxism.com/thing-translator/thing-translator.gif)

![](https://oxism.com/thing-translator/img/1.jpg)

![](https://oxism.com/thing-translator/img/2.jpg)


## How it works ?

Concepts present in captured image are extracted and translated to the given language.

It uses

- [Clarifai's](https://clarifai.com/) concept recognition from images
- [Yandex's](https://tech.yandex.com/translate/) language translation.

## Try it ?

Have a look at the [React-native Docs](https://facebook.github.io/react-native/docs/getting-started.html) to set up a development environment for React-native and Android.

```sh
# Install react-native
$ sudo npm install -g react-native-cli

# Clone repository
$ git clone https://github.com/thordenson/what_the_thing.git
$ cd what_the_thing

```


```sh
# Install required packages
$ yarn install || npm install

# Install the application on a running Android emulator or a connected Android device
$ react-native run-android

# Run the server/bundler
$ react-native start

# Done !
```

<hr/>


## Contribute ?

- Fork the repository
- Commit your changes
- Submit a pull request

## Licence

[MIT Licence]