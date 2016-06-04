# burffee
--------------

burffee is a pattern that could possibly be used to develop UI for the web.The concept is still at a very early stage of development and needs a good deal of validation.

Motivation
--------------
UIs have predominantly used CSS/JS to detect external events. And as div tags are essentially rectangular ,
the scope for expressive UI has been a little bit contrained. Would it be different/better if we have UI elements that are polygonal in nature? 
Although svg does allow for polygonal shapes , its ability to be a good UI element with perfomance comparable to the simple div tag is something
that prompts for a relook.

Pattern
--------------
Have a canvas tag as a hit detection layer with an img tag underneath it as a display/animation layer.

First attempt 
--------------
Developed [intron](https://github.com/moondram832001/intron) - a simple avatar widget based on [React](https://facebook.github.io/react/) and [konva](http://konvajs.github.io/)/[kineticjs](http://www.kineticjs.com/) libraries.
