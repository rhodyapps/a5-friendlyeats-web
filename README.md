# FriendlyEats (Web)

## Comsc230 TN

This is a modified version of the Google Codelab 'Friendlyeats Web'

1. On your computer you need Node JS download from: https://nodejs.org/en/
2. Next, clone this repo.
3. In VS Code, open the folder for the repo and start a new terminal
4. Log in to the Firebase console: https://console.firebase.google.com/
5. Add a new project 'friendlyeats-web'
6. Enable 'Anonymous Auth' ( Click on Authentication> Sign In Method )
7. In V COde Terminal: npm -g install firebase-tools (if you get EACCESS errors put 'sudo' in fromt of this command and run it again)
8. VS Code Terminal: firebase --version
9. VS Code Terminal: Firebase login
10. VS Code Terminal: firebase use --add (choose your project and enter 'default' for an alias)
11. Run the local server in VS Code Terminal: firebase emulators:start --only hosting 12. Open your app at http://localhost:5000.


## Introduction

FriendlyEats is a restaurant recommendation app built on Cloud Firestore.
For more information about Firestore visit [the docs][firestore-docs].

This project is the starting point for the [Cloud Firestore Web Codelab][codelab],
which will show you how to build the applications step-by-step. If you'd like to
simply run the finished result, see the [quickstart app][quickstart].

<img src="docs/finished_image.png" />

## Setup

Follow the [Cloud Firestore Web Codelab][codelab] to set up this sample.

## License

© Google, 2018. Licensed under an [Apache-2](./LICENSE) license.

## Build Status

[![Build Status](https://travis-ci.org/firebase/friendlyeats-web.svg?branch=master)](https://travis-ci.org/firebase/friendlyeats-web)

[codelab]: https://codelabs.developers.google.com/codelabs/firestore-web
[quickstart]: https://github.com/firebase/quickstart-js/tree/master/firestore
[firestore-docs]: https://firebase.google.com/docs/firestore/