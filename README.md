Am I Flipping Off My Computer?
==============================

##Screenshot

![Screenshot](http://i.imgur.com/JvGgdsf.png)

Created for LA Hacks 2014.

##Technical Details

* Leap Motion SDK, although possibly internally, does not externally offer finger type identification.
* We decided to solve this problem in a fun way.
* Using vector dot products between palm direction vectors and the displacement vector from palm center to knuckle (which itself is computed with finger tip location vector minus length in the direction the finger is pointed), we can classify fingers to some extent.
* You can also combine our detection with finger length to improve accuracy.

##Inspired By

* https://isitchristmas.com
