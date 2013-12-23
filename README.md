arduino
=======

My Arduino Projects

PIR Sensor - this is sample code for triggering a pin to high when motion is detected. I followed the same steps 
in the makezine article 'couch monkey guardian' (http://makezine.com/projects/monkey-couch-guardian/) to 
trigger a halloween doorbell for my kids.

LCD-Scroll - this is sample code for scrolling text on a 2x16 lcd screen. I found the built in scrolling functions
not useful, so I created one using a character array.

Twitter to LCD - this arduino script will read an html file and display the contents on the LCD. I have my webserver 
connected to my twitter account, displaying my twitter feed in a simple 2 line format. The arduino connects to my 
webserver and displays the contents on the lcd. You can see it in action here: http://youtu.be/XnlK4zlACsE
- Dec 20 2013: Updated code to connect to 123Ticker.com (my webserver), rather than IP address. Added ability for others to connect to their twitter account thru 123ticker.com. Register at 123ticker.com, then replace the account key with the one assigned to you in get_html() below.



