# README

Create a JavaScript music player with the ability to play, pause, forward, change images when music changes. The player will have a timer to show the status of the song. Will also have the ability to have songs play on a loop.

* Audio/Video Methods, Attributes, etc. References Used: https://www.w3schools.com/tags/ref_av_dom.asp

* ProgressBar check srcElement events for currentTime and duration

* setProgressBar check srcElement and find clientWidth, use this.clientWidth to set the width of the bar. Find offsetX to find where I clicked

* Using textContent vs. inneText - textContent returns all elements including script and style elements. While innerText only shows 'human-readable' elements, it will not return text of hidden elements.

* title= attribute where shows as tooltip in chrome doesn't work.  Fix: show tabindex="-1" on the parent element and it appears.
