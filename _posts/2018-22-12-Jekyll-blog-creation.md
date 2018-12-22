---
layout: post
title: Jekyll Blog creation
image: /img/yt.png
tags: [How to, Tech]
---

## Introduction

I always wanted to have a "blog" to post and share as I go, but I wanted a convenient way of doing it, let's face it you want to setup a Wordpress, you have a lot of flexibility but you end up working on the setup for days without having a chance to really focus on the most important **content**

I was scrolling on Instagram 2 days ago, and came across to the story of [paul_3d_things](https://www.instagram.com/pauls_3d_things/) ( very good content you guys should defo follow him! ) I've message him and ask him about his setup, he told me he was using [Jekyll](https://jekyllrb.com/), I've take a look and I can say after 2 days that the setup is very convenient, below this will be my attempt to explain how I setup my blog.

## Setup

Having the blog without having the need to login on the backend, been able to do that from your editor is super nice, allowing you once you are traveling or having 5 min to work on your articles. This is what I'm able to do as I speak using [Jekyll](https://jekyllrb.com/) + [GitHub](https://github.com/) & [Atom](https://atom.io/) - The blog is actually hosted on GitHub ( meaning that you don't need to have an external hosting for the site itself no backend for the DB etc ) and Jekyll is the "bootstrap" running in the background, Atom is my editor where I create the post using markdown and allow me to commit and push new content to GitHub and the blog got updated.

![Blog Creation](https://i.gyazo.com/28126c84a826e4f5d2162c6b5294cd97.png)

### 1 Dependency & Installation

You would need to download and install [the Ruby Dev kit](https://rubyinstaller.org/downloads/) in order to be able to do a preview of your modification prior to publishing this on github by using the git terminal and typing: _jekyll serve ._

Once Ruby is installed you can go ahead and install bundler + Jekyll which will allow you to locally test your modification prior to pushing it to GitHub.

On your prompt, type: _gem install bundler jekyll_

![Jekyll is installed](https://i.gyazo.com/6463b356b50ea5cc94ef65ff80dbd138.png)

at this stage we are finish with the jekyll installation - we don't need Jekyll to create a new site since we're using a template ( if you're having some trouble installing jekyll, you might want to start with _gem install bundle_ first and then type _bundle install_)

### 2 Template

Few template website are listed on the [Jekyll](https://jekyllrb.com) - After giving few try, I end up having the template from [daattali](https://github.com/daattali/beautiful-jekyll)

### 3 Atom

[Atom](https://atom.io) is a nice Editor which I recommend using, for us maker and electronics enthusiast the editor is also compatible with a bunch of card such as Arduino/NodeMCU/ESP8266 ... I can commit and push all my change on the fly and this is what I was looking for!

### Conclusion

The blog will be a platform for me to document and share my finding, which will also contain any of my video, hopefully you might find something useful, I'd like to engage with you on the social media as well, if you have any question feel free to reach out to me - I'm up for any inspiration in project!
