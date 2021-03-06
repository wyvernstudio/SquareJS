# ![LINE](https://github.com/GoogleX133/LINE-WebChat/raw/master/public/images/small.png) LINE SquareJS-Bot
[![NPM](https://img.shields.io/badge/npm-%3E=%205.5.0-blue.svg)](https://nodejs.org/) [![Node](https://img.shields.io/badge/node-%3E=%208.0.0-brightgreen.svg)](https://nodejs.org/) [![AUR](https://img.shields.io/aur/license/yaourt.svg)](https://github.com/GoogleX133/LINE-FreshBot/blob/master/LICENSE) [![LINE](https://img.shields.io/badge/line-%207.18-brightgreen.svg)](http://line.me/) [![Contact Me](https://img.shields.io/badge/chat-on%20line-1bacbc.svg)](http://line.me/ti/p/MB6mnZWbu_) [![Version](https://img.shields.io/badge/beta-1.0-brightgreen.svg)](https://github.com/GoogleX133/LINE-FreshBot)<br><br>
LINE Messaging Web Private Platform

----

PAGES
=====

- [What is LINE SquareJS ?](#what-is-line-squarejs-)
    - [Keyword](#keyword)
    - [Upcoming Feature](#upcoming-update)
- [Requirement](#requirement)
- [Installation](#)
    - [Windows](#windows-installation)
    - [Linux](#linux-installation)
    - [Termux](#linux-installation)
    - [Setup](#line-squarebot-setup)
- [How to run](#how-to-run)
- [How to get ChatMid](#how-to-get-chatmid-for-square)


## What is LINE SquareJS ?

LINE SquareJS is an unofficial *LINE Messaging Private Bot*

## Keyword

Type `help` to see the keyword

## Upcoming Update

- More async function lib

<br><br>
If you have an idea for new feature, you can contact [me](https://line.me/ti/p/~@lmu8345a).

## Requirement

This repo require a [NodeJS With Node](https://nodejs.org/) >= 8.0.0.

## Windows Installation

First of all, you need to install [Git](https://git-scm.com/download/win) & [NodeJS](https://nodejs.org/). Then open your git bash, and follow this:<br>
```sh
$ git clone https://github.com/wyvernstudio/SquareJS.git
$ cd SquareJS
$ npm i
```

## Linux Installation

```sh
$ apt-get update
$ apt-get install curl
$ apt-get install git
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -
$ apt-get install nodejs
$ git clone https://github.com/wyvernstudio/SquareJS.git
$ cd SquareJS
$ npm i
```

## LINE SquareBot Setup

After you install with `npm i `, all you have to do is insert your squareChatMid on `var sqChatMid = 'HERE';` at ./examples/square.js

## How to run

You can run with (talk bot)<br>
```sh
$ node ./examples/talk.js
```
<br>or (square bot)<br>
```sh
$ node ./examples/square.js
```

## How to get ChatMid (For Square)

Simple, you just run this script<br>
```sh
$ node ./examples/getchatmid.js
```

## Credits

GoogleX133 https://github.com/GoogleX133/LINE-FreshBot
