# Electron.js 101
## References
- [Docs](https://electronjs.org/docs)
- [Medium article on optimization](https://medium.com/@felixrieseberg/javascript-on-the-desktop-fast-and-slow-2b744dfb8b55)

## Overview
Notes for Electron.js development are placed here. Electron is a variation of the Node.js runtime which allows you to build desktop native apps with all of the web-native tools we like.

## Starting The App

## Performance Optimization
There's a whole bunch of ways to optimize performance of an Electron app. The first thing you really should be doing is using the Chrome Web Tools to check where your app is lagging behind. As Electron runs on Chromium, functionally you're building a web app so you can optimize your Electron app like it's a web app.