# Message Cleaner [![CodeFactor](https://www.codefactor.io/repository/github/slow/message-cleaner/badge)](https://www.codefactor.io/repository/github/slow/message-cleaner) [![GitHub issues](https://img.shields.io/github/issues/slow/message-cleaner?style=flat)](https://github.com/slow/message-cleaner/issues) [![GitHub stars](https://img.shields.io/github/stars/slow/message-cleaner?style=flat)](https://github.com/slow/message-cleaner/stargazers) [![Support](https://img.shields.io/discord/875126204758360094)](https://discord.gg/shnvz5ryAt)

A powercord plugin to prune messages.

# Requirements

-  Powercord

# Installation

-  `git clone https://github.com/slow/message-cleaner`

# Previews

![Preview](https://i.imgur.com/GvPunQp.png)
![Preview](https://i.imgur.com/e9tgbwO.png)

# Usage

-  `clear all beforeId`
-  `clear number beforeId`
-  `prune all beforeId`
-  `prune number beforeId`

# Adding your own aliases

### To add your own aliases, you must find your powercord settings folder.

-  Go to [powercord folder location]\settings\message-cleaner.json
-  To add an alias add another array item by changing `['1', '2', '3']` to `['1', '2', '3', '4']`
-  The order of it doesn't matter.

# Examples

-  `clear all`
-  `clear all 739493961713975368`
-  `clear 10`
-  `clear 10 739493961713975368`
-  `clear stop`
-  `prune all`
-  `prune all 739493961713975368`
-  `prune 10`
-  `prune 10 739493961713975368`
-  `prune stop`
