---
author: Nick Brown
pubDatetime: 2023-03-12T11:19:10.413Z
title: Add OpenAI ChatGPT to your Siri (iPhone)
postSlug: add-openai-chatgpt-to-siri-iphone
featured: true
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - openai
  - chatgpt
description: AstroPaper with the enhancements of Astro v2. Type-safe markdown contents, bug fixes and better dev experience etc.
---

Recently, I have been using OpenAI's ChatGPT on a daily basis. Even during work, sometimes where previously I'd ask StackOverflow a code question, I've been first consulting my Co-pilot (no, not you GitHub Co-pilot), my buddy - **ChatGPT**. Which has, in most cases saved me from needing to browse through the last decade of answers and find the latest accepted best practice.

I have an iPhone and I don't use Siri all that much (aside from setting alarms and timers). So I wondered if I could replace Siri (or rather, enhance, sorry Siri if I hurt your feelings) with the OpenAI chatbot.

_As it turns out that is already pretty common and it's pretty easy to do._

# How To

There's only really three steps to setting it up.

## 1. Get an OpenAI API Token

First you'll need to login to OpenAI (or create an account if you don't have one).

1. Head to https://platform.openai.com/ and login.
2. Navigate to your account details (top-right) and then open "**View API keys**".
3. `+ Create new secret key` and then copy the key and store it somewhere like a Notepad / TextEdit (or just your clipboard if you live life fast and loose) for later on.

## 2. Download a Shorcut for Siri

A developer [YueYang](https://github.com/Yue-Yang) has created a public repository with links to iterations of the ChatGPT Siri shorcuts.

The repository reads:

> Shortcuts for Siri using ChatGPT API gpt-3.5-turbo model, supports continuous conversations, configure the API key & save chat records.

**Note**: The following steps should be done on your iPhone.

1. Head to the repository: https://github.com/Yue-Yang/ChatGPT-Siri

2. Scroll down to ChatGPT Siri 1.2 and grab the "English Version" (I made an assumption since you're reading this post).
   1. Alternatively, here's a link directly to the iCloud shortcut "ChatGPT 1.2": https://www.icloud.com/shortcuts/dfa38b2abb58470380086dc4b5d50143
   2. You may change the name of this shortly.

There are other Siri/ChatGPT shortcuts out there. I just like how this one operates.

## 3. Add your API Token to the Shortcut

Go into the Shortcuts application and add your API token copied in Step 1.

Now, you should be able to activate Siri with the "Hey, Siri!" and then say "ChatGPT 1.2". This will activate the Shortcut and enable a verbal input into ChatGPT. An Siri will read you the response!

`Hey Siri, ChatGPT 1.2`

But, you can change it to whatever you like to activate the shortcut, which I'd recommend.

Just simply rename the shortcut.

I would say ChatGPT 1.2 is a bit of a mouthful, but I have a weird sense of humour and went with:

`Hey Siri, it's big brain time!`

Which activates my ChatGPT buddy.

But other normal people might go with `Siri Pro` or just `ChatGPT`. But that's lame.

## Enjoy having the power of OpenAI at your beck and call!

P.S. I use it from my Apple Watch which is also fun if you have one.

Thanks for reading!
