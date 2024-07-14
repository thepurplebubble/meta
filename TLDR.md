

# Introduction


We're Purple Bubble, a crew of teens on a mission to make messaging epic again! Tired of feeling like the product in those other apps? We get it. That's why we're building something new: an app that puts YOU in control. No ads, no data mining, no creepy algorithms. Just you, your friends, and a whole lot of fun.

We're in the super-early stages (think building a pillow fort!), and we're looking for awesome testers to join our inner circle. You can sign up for our newsletter at [purplebubble.org](purplebubble.org) - we promise it'll be way more exciting than your dentist's newsletter. 4-5 updates a year, no spam.

> **Wanna chat?**
>
> We mostly communicate through the [Purple Bubble Slack](https://join.slack.com/t/thepurplebubble/signup), but you can also email us (team@purplebubble.org) or open a Github issue.
 

## Protocol

Protocol v1.0.0 Jasper has multiple REST API servers in a mesh network. Clients pick two servers. One is used for transmission (TX) and the other is used for reception (RX). For faster messaging users can switch to Transparent Mode, which uses an encrypted STUN server to establish a WebRTC connection. Messages are signed by users' keys.

## App

We currently plan to have a desktop and mobile app. You'll be able to sign in using a key file that holds your public and private key, and your friends can add you by importing a contact file that holds your public key, name, and preferred profile picture.