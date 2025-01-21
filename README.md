[![Build Status](https://github.com/nopid/GameOn/workflows/Build/badge.svg)](https://github.com/nopid/GameOn/actions?query=workflow%3ABuild)

![TIC-80](https://tic80.com/img/logo64.png)
**TIC-80 TINY COMPUTER** - [https://tic80.com](https://tic80.com)

# About
TIC-80 is a free and open source fantasy computer for making, playing and sharing tiny games.

This repository is a fork from [https://github.com/nesbox/TIC-80](https://github.com/nesbox/TIC-80). Please refer to the official repository for due credits to the creators of this wonderful tool.

This TIC-80 html edition is twisted in the following ways:
 1. a new `sel` command to access the internal clipboard from the browser;
 2. a patched version of [msf_gif](https://github.com/nopid/msf_gif) to support Screenshots and Video recording in the browser;
 3. crude modifications of the networking code to serve carts from static json files on our server;
 4. default config alterations (dev mode by default, AZERTY keyboard gamepad configuration).

