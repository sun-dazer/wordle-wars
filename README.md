# [Wordle Wars](https://wordlewars.ctnicholas.dev)

This repo shows how to build a multiplayer Wordle clone with [Liveblocks](https://liveblocks.io), [Vue](https://vuejs.org/), and [Vite](https://vitejs.dev/).
This repo aims to show users how to build a multiplayer Wordle clone utilizing Liveblocks, Vue, and Vite. This repository is forked from 
## [Try it out](https://wordlewars.ctnicholas.dev)

## Project Description
This project recreates the popular New York Times game, Wordle. Wordle rotates out a daily word at UTC 00:00. Players aim to guess the word within 6 attempts, with highlighted squares telling them which letters are utilized. Our version of this game adds a multiplayer function as well as extra styling. Users can only see the opponent's letters after they complete the game, solving the word of the day. Scores are saved at the end through a user profile feature. It features a dark mode and a colourblind mode.
![Wordle wars screenshot](https://wordlewars.ctnicholas.dev/screenshot.png)

## Getting started

### Run examples locally

- Install all dependencies with `npm install`

- Create an account on [liveblocks.io](https://liveblocks.io/dashboard)

- Copy your public key from the [administration](https://liveblocks.io/dashboard/apikeys)

- Create a file named `.env.local` and add your Liveblocks secret as environment variable `VITE_LIVEBLOCKS_PUBLIC_KEY=sk_test_yourkey`

### Run examples on CodeSandbox

- Open this repository on CodeSandbox with this [link](https://codesandbox.io/s/wordle-wars-with-liveblocks-and-vite-0hhdi)

- Create an account on [liveblocks.io](https://liveblocks.io/dashboard)

- Copy your public key from the [administration](https://liveblocks.io/dashboard/apikeys)

- Create [secret](https://codesandbox.io/docs/secrets) named `VITE_LIVEBLOCKS_PUBLIC_KEY` with the secret key you just copied. You need to create an account on CodeSandbox to add an environment variable.

- Refresh your browser and you should be good to go!

## Contributer Guide
We welcome contributions to this project! Here is how you can help:
1) Fork the Repository 
    - Click the "Fork" button at the top right of this page
2) Clone Your Fork
    - Clone your forked repository to your local machine: `git clone https://github.com/your-username/repository-name.git`
    `cd repository-name`
3) Create a Branch
    `git checkout -b feature-name`
4) Make your changes
5) Push to Your Fork
    - `git push origin feature-name`
6) Open a Pull Request

# Guidelines
Code Style: Follow the existing code style used in the project.
Documentation: Update the documentation if your changes affect how the project works.
Issue Tracking: Please reference the issue number in your pull request

## Credits
This project is forked from [Vue Wordle](https://github.com/yyx990803/vue-wordle) created by Evan You (@yyx990803). This repository is open sourced for learning purposes only - the original creator(s) of Wordle own all applicable rights to the game itself.
