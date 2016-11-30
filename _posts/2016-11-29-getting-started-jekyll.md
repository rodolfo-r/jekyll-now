---
layout: post
section-type: post
title: Getting Started with Jekyll
category: Tutorial
tags: [ 'jekyll', 'blog' ]
---

## What we will be building  
A free blog, the developer way.
## Why have a blog as a developer?  
* Having a blog as a developer will put you as an *authority* among the dev community.  
* You will be more *hirable* by employers. Nothing demonstrates domain expertise like a public showcase of it.  
* You will *learn* more efficiently by teaching via the [“Feynman Technique”](http://mattyford.com/blog/2014/1/23/the-feynman-technique-model)  
## What is **Jekyll**?  
Jekyll is a static site generator.  
What that means is that it creates your website from the files you give it. You **don’t have to worry about the complexities** that go along with generating a complex blog. All *you* have to do is give it a file written in markdown, and poof: You have another post on your blog!  

## Why **Jekyll**?
### You can do it yourself
Why not use a drag and drop website creator? like weebly.com or squarespace.com or wix.com? You can just pay a couple of bucks and you have a website that you can customize with so many of their themes! Well you could, sure. But we are **developers**, and we can’t pay money for something we know we can do, and better.
We’re like your mom who critiques the food when you go out eating saying she can do a better job at home (I’m not the only one, right?).

### Autonomy
Whenever something fails, (or succeeds) it’s entirely because of you. You are the ship commander, not the passenger. Leaving things up to the website provider is both good and bad: good because you can worry about other stuff instead, bad because you don’t have any control. If you seek to add a new feature to your site: tough luck. You either have to *pay up*, or *suck it up* if what you want isn’t offered.

### It’s FREEEEE
Hosting on [GitHub Pages](https://pages.github.com/) is completely free. That is the reward for building things yourself. The only thing you will have to pay for (and that’s only if you want to) is for the domain. You can run your website for years, iterate on its development, do whatever you want with it, without ever paying for hosting. Pretty dope.

### Learning
Even if you only do the setup and never write a blog post on your site, you will at least have a new skill to put on your resume. And you will have become a better developer, even if by a little bit.

## Requirements:
* Linux or macOS (Preferred)
* [Homebrew](http://brew.sh/) (for Mac, not required)
`$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)”`
### You can use your package manager for only some of these:
* [Git](https://git-scm.com/downloads)
* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [RubyGems](https://rubygems.org/pages/download)
* [NodeJS](https://nodejs.org/en/)
`$ brew install node`
* [Python](https://www.python.org/downloads/)
`$ brew install python3`
* [Jekyll](https://jekyllrb.com)
`$ gem install jekyll`  
## Jekyll Themes: The starting point
You’re going to want to use a theme as a starting point for the blog
The best resource would be: [JekyllThemes.org](http://jekyllthemes.org/), but really anything works.
For this tutorial, we’re going to use Luka-H’s [Onepage Theme](https://github.com/lukas-h/onepage) The reason for this is this is that Onepage is very simple, perfect for understanding what we need to understand.
You can fork the repo we will be using [here](https://github.com/techmexdev/Getting-started-with-Jekyll)
## Setup
The setup should be quite easy, since all we need are *three terminal commands*
### First install the repo on your machine
`$ git clone https://github.com/techmexdev/Getting-started-with-Jekyll.git) `
Go to it’s directory
`$ cd Getting-started-with-Jekyll`
Build server locally
`$ jekyll serve`
Ta-da! You should see a preview in your browser @ localhost:4000!
## Adding your  personal data
	* The Config File: Personal data will reside in: `_config.yml`
## Creating Posts
	* The Posts folder
