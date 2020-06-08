---
layout: post
title: Reminders App
subtitle: Building a simple suggestion app
tags: [iOS]
---

Learning how to send notifications in iOS and create reminders was a fun task. The project was inspired by the book "5 Love Languages" and was simple. The user gets daily reminders to do some sort of romantic gesture.  

## Notifications

Originally I wanted the app to send notifications. However, after some research that would require a server to send the notifications and that was more infrastructure then desired for this simple app.
Later I found a way to create local notifications but with how this app sent out daily notifications it would then need to store all the notification info to delete them in case the user wanted to stop, or changed preferences, etc. It was a mess.

## Reminders

So to simplify the project it uses the existing native iOS app Reminders to keep track of notifications. The app creates a list and stocks it full of reminders. Now, users can view, edit, and delete reminders instead of me having to do the duplicate building. If it already exists why build it? 
