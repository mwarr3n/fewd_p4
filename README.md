
## Website Performance Optimization portfolio project

### Getting started 
Live version of the code can be found:

[http://mwarr3n.github.io/udacity/p4](http://mwarr3n.github.io/udacity/p4)

####Part 1: Optimize PageSpeed Insights score for index.html

Utilized PageSpeed Insights and techniques from Website Performance Optimization course.

Page: index.html
* Modified google font reference: lines 10-16.
* Converted style css to a javascript: lines 18-31.
* Added media meta tag to print.css: line 34.
* Added asynch to scripts: line 44 and 45

Minified 	
* css/style.css -> css/style.min.css

####Part 2: Optimize Frames per Second in pizza.html

Page: main.js
* modified changePizzaSizes function. Moved variables outside the loop.Converted querySelectAll -> getElementsByClassName: Lines 451-469.
* Moved variable deceleration out side of loop: lines 483-485.
* declared items variable outside of function updatePositions: line 515 and 521.
* move calculation outside of loop: line 524.
* declared variable outside of loop and converted querySelector -> getElementById : line 549 and 562.
* defined items. Originally defined on 521: line 567.
* modified pizza count from 200 to 40: line 552.

Minified 	
* views/css/style.css -> views/css/style.min.css
* views/js/main.js -> views/js/main.min.js


###Resources/tools 
* [https://www.google.com/fonts](https://www.google.com/fonts )
* [https://developers.google.com/speed/pagespeed/insights/](https://developers.google.com/speed/pagespeed/insights/)
* [http://jscompress.com](http://jscompress.com) 
* [http://csscompressor.com](http://csscompressor.com) 
* [Piazza Forum](https://piazza.com/class/i23vpy8h7l27la?cid=550) 
