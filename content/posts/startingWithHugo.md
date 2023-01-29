---
title: "Starting With Hugo"
date: 2023-01-29T15:57:23-05:00
draft: false
---

# Building this site

My site before [this](https://github.com/no-budy/nobudyxyz) was built by hand to learn HTML and CSS. I was excited to have something of my own online but it quickly became neglected because I didn't have an easy way to add new posts. I would have to login to my server and manually add what I wanted by writing a new page in HTML.

I had learned what Hugo was a while ago while trying to find an easier way to make a good looking site that was easy to manage. I wanted this to be MY site that I had control over so there was never any chance of me using some site maker, ten dollar a month, website as a service scam. A good static site generator would let me have a complete and complex site without having to do too much by hand. Enter Hugo.

![hugo](/hugo.png)

## Why hugo?

"Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again."

A quote directly from their website that I can now vouch for. First off Hugo is incredibly fast. They've achieved render times of less than a milisecond depending on the page. So no matter if you are rendering a small personal blog like this or something as large as a wiki, Hugo can do it in a blink. 

Another enticing feature is the themes. You can create your own or you can use and modify one that someone else created. I'm using the poison theme which is a great starting point. Its simple and leaves plenty of room of you to customize.

Hugo also has some features that you might not find in some other generators such as shortcodes. These let you take large and clunky bits of HTML that you would have to add by hand like youtube embeds and turn them into concise codes to drop in your markdown file and forget about.

For example this youtube embed

```<iframe width="560" height="315" src="https://www.youtube.com/embed/Kfek3TMPvPo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>```

Gets shorted to just this

```{{</* youtube Kfek3TMPvPo */>}}```

While your messing around with your markdown in one window you can have the `hugo server` running and serving up all the changes in real time to a browser, making for easy iteration and proof reading. 

## Future plans

Now that I have my own Hugo site I can keep learning more about the feature set that is available to me. I'd like to look into tags and grouping content but this is a good start. 
