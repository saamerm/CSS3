# CSS3
++++++++++

https://css-tricks.com/snippets/css/a-guide-to-flexbox/
CSS Flexbox tutorial
A
============
/*FontSquirrel ->Most popular->Very long procedure, download webkit. Install the code on your computer....
fonts.google.com best place to get fonts. Roboto, second icon (Quick code), Bold 700 and alternate ones above.
Take the html code and place it in the <head>
<link href='https://fonts.googleapis.com/css?family=Roboto:400,700,500,300' rel='stylesheet' type='text/css'> </head>
and the style sheet and put it in your CSS code.
h1,h2,h3,p,li,a { font-family: 'Roboto', Arial, serif; font-weight: 1000; }
Google Hosts and Licenses it for free*/

===========
B
++++++++++++
/* css Zen Garden default style v1.02 css released under Creative Commons License - http://creativecommons.org/licenses/by-nc-sa/1.0/  
This file based on 'Tranquille' by Dave Shea  You may use this file as a foundation for any new work, but you may find it easier to start from scratch.
Not all elements are defined in this file, so you'll most likely want to refer to the xhtml as well. */

/* Your images should be linked as if the CSS file sits in the same folder as the images. ie. no paths. */


/* basic elements */
html {
	margin: 0;
	padding: 0;
	}
body { 
	font: 75% georgia, sans-serif;
	line-height: 1.88889;
	color: #555753; 
	background: #fff url(http://csszengarden.com/001/blossoms.jpg) no-repeat bottom right; 
	margin: 0; 
	padding: 0;
	}
p { 
	margin-top: 0; 
	text-align: justify;
	}
h3 { 
	font: italic normal 1.4em georgia, sans-serif;
	letter-spacing: 1px; 
	margin-bottom: 0; 
	color: #7D775C;
	}
a:link { 
	font-weight: bold; 
	text-decoration: none; 
	color: #B7A5DF;
	}
a:visited { 
	font-weight: bold; 
	text-decoration: none; 
	color: #D4CDDC;
	}
a:hover, a:focus, a:active { 
	text-decoration: underline; 
	color: #9685BA;
	}
abbr {
	border-bottom: none;
	}


/* specific divs */
.page-wrapper { 
	background: url(http://csszengarden.com/001/zen-bg.jpg) no-repeat top left; 
	padding: 0 175px 0 110px;  
	margin: 0; 
	position: relative;
	}

.intro { 
	min-width: 470px;
	width: 100%;
	}

header h1 { 
	background: transparent url(http://csszengarden.com/001/h1.gif) no-repeat top left;
	margin-top: 10px;
	display: block;
	width: 219px;
	height: 87px;
	float: left;

	text-indent: 100%;
	white-space: nowrap;
	overflow: hidden;
	}
header h2 { 
	background: transparent url(http://csszengarden.com/001/h2.gif) no-repeat top left; 
	margin-top: 58px; 
	margin-bottom: 40px; 
	width: 200px; 
	height: 18px; 
	float: right;

	text-indent: 100%;
	white-space: nowrap;
	overflow: hidden;
	}
header {
	padding-top: 20px;
	height: 87px;
}

.summary {
	clear: both; 
	margin: 20px 20px 20px 10px; 
	width: 160px; 
	float: left;
	}
.summary p {
	font: italic 1.1em/2.2 georgia; 
	text-align: center;
	}

.preamble {
	clear: right; 
	padding: 0px 10px 0 10px;
	}
.supporting {	
	padding-left: 10px; 
	margin-bottom: 40px;
	}

footer { 
	text-align: center; 
	}
footer a:link, footer a:visited { 
	margin-right: 20px; 
	}

.sidebar {
	margin-left: 600px; 
	position: absolute; 
	top: 0; 
	right: 0;
	}
.sidebar .wrapper { 
	font: 10px verdana, sans-serif; 
	background: transparent url(http://csszengarden.com/001/paper-bg.jpg) top left repeat-y; 
	padding: 10px; 
	margin-top: 150px; 
	width: 130px; 
	}
.sidebar h3.select { 
	background: transparent url(http://csszengarden.com/001/h3.gif) no-repeat top left; 
	margin: 10px 0 5px 0; 
	width: 97px; 
	height: 16px; 

	text-indent: 100%;
	white-space: nowrap;
	overflow: hidden;
	}
.sidebar h3.archives { 
	background: transparent url(http://csszengarden.com/001/h5.gif) no-repeat top left; 
	margin: 25px 0 5px 0; 
	width:57px; 
	height: 14px; 

	text-indent: 100%;
	white-space: nowrap;
	overflow: hidden;
	}
.sidebar h3.resources { 
	background: transparent url(http://csszengarden.com/001/h6.gif) no-repeat top left; 
	margin: 25px 0 5px 0; 
	width:63px; 
	height: 10px; 

	text-indent: 100%;
	white-space: nowrap;
	overflow: hidden;
	}


.sidebar ul {
	margin: 0;
	padding: 0;
	}
.sidebar li {
	line-height: 1.3em; 
	background: transparent url(http://csszengarden.com/001/cr1.gif) no-repeat top center; 
	display: block; 
	padding-top: 5px; 
	margin-bottom: 5px;
	list-style-type: none;
	}
.sidebar li a:link {
	color: #988F5E;
	}
.sidebar li a:visited {
	color: #B3AE94;
	}


.extra1 {
	background: transparent url(http://csszengarden.com/001/cr2.gif) top left no-repeat; 
	position: absolute; 
	top: 40px; 
	right: 0; 
	width: 148px; 
	height: 110px;
	}
