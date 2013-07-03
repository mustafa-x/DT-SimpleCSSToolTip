#DT-SimpleCSSToolTip
##A really simple Tooltip made purely in CSS

This little project shows you how create a tooltip in CSS. Currently its work in progress so there may be some buggyness :)

It uses HTML5 Data attribute to populate the CSS "content" property. So if you have mark up like this;

	<div data-somecontent="this is my conten"> hi there. </div>

Then use a CSS selector

	div {
		content: attr(data-somecontent);
		display: block;
	}

This adds the data into the div container. With some more CSS magic we can turn it into a tooltip like this: 

Demo: http://cdpn.io/oCqIu

##Contact
- Twitter: http://twitter.com/mustafa_x
- Site: http://designtoday.info

##License
Llicensed under CC BY 3.0:
http://creativecommons.org/licenses/by/3.0/
A mention of 'DT-phpAccordian' in human-readable source code is considered acceptable attribution (most common on theweb). If human readable source code is not available to the end user, a mention in an 'About' or 'Credits' screen is considered acceptable (most common in desktop or mobile software) but not required.
