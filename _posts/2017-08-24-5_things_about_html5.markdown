---
layout: post
title:  "5 Updates About HTML5"
date:   2017-08-24 09:02:23 -0400
---


Here are my top 5 notable updates that HTML5 offers.

1. Videos:

In regular HTML, videos were played through a browser and required a plug-in (ex: Flash). We all remember how annoying those can be.

Now, with the HTML5 video element, you can embed a video directly into a web page. Speaking of Flash...

2. Graphics / Animation:
 
In HTML, the way to render graphics and animation on a site was through Flash.

HTML 5's new canvas element can used instead of Flash to draw graphics via JavaScript. Note that the canvas element is only a container for graphics. You'd still have to use JavaScript to draw the graphics. Canvas has several methods for drawing various shapes, paths and adding images.

3. The DOM:

Another difference is that HTML5 provides full support for JavaScript to run in the background (thanks to the JS web worker API of HTML5). For example, the HTML5 DOM has methods, properties, and events for the audio and video elements which allow you to manipulate these elements using JavaScript.

4. Semantics:

These semantics have been put in place and standardized according to popular use.

Header:
HTML: div id ="header"
HTML5: header

Left Rail:
HTML: div id = "menu"
HTML5: nav

Content:
HTML: div class = "post"
HTML5: article

Footer:
HTML: div id ="footer"
HTML5: footer

5. Local Storage:

Before HTML5, application data had to be stored in cookies included in every server request (to remember your preferences, login state, etc). Note that cookies can only hold a small amount of data.

With HTML5's local storage, web applications can store data locally within the user's browser. The local storage object is a part of the global window namespace and can be accessed from wherever desired while using scripts. Local storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data. Unlike cookies, local storage doesn't slow down browsing performance, the storage limit is far larger (at least 5MB) and information is never transferred to the server, making it more secure.

