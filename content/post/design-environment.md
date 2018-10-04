+++
title = "Design Environment for Game Development"
date = 2018-10-04T16:02:29+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["libgdx", "android", "settings"]
categories = []

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = true

+++

# Getting started

In this article I would like to show what is required to have an up and ready environment for
game development with the *libgdx* framework. There is a getting started page on the libgdx's website, but I wanted to gather all the required steps in one place. I will focus on what is needed for a 2D Game Developer who is targeting **Android** mainly. I'm using Ubuntu 18.04 right now, but probably fellow windows, macOS users can follow along.  

We're going to install and setup the following tools:

* java
* gradle
* android
* IntelliJ (skip if you're using other IDE)

## Java

```
$ sudo add-apt-repository ppa:webupd8team/java -y
$ sudo apt-get update
$ sudo apt-get install oracle-java8-installer
```
Set Oracle Java 8 as default
```
$ sudo apt-get install oracle-java8-set-default
```
Verify the installation was successful
```
$ java -version
java version "1.8.0_181"
Java(TM) SE Runtime Environment (build 1.8.0_181-b13)
Java HotSpot(TM) 64-Bit Server VM (build 25.181-b13, mixed mode)
```