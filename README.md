Overview
===========

This code adds bugs to your Kintone environment. 
This code utilizes the Bug library http://auz.github.io/Bug/ made by @Auz  
Released under WTFPL license.

How to Use
===========

1. Prepare a Kintone App ready with Process Management Settings enabled
2. Copy the bug.js code into an editor and set the following constants:
- appID -> the App Id of the App you created in Step 1. This is a number that you'll find in the URL of the App.
- statusname -> the string of the Status name which will trigger the release of the bugs. This is case sensitive. 
- username -> the user that you want to release the bugs to. Specify the log in name string. This is case sensitive.
Save the file after making the changes.
3. Upload the JavaScript file to the System Wide JavaScript and CSS Customization settings  
https://get.kintone.help/hc/en-us/articles/115001237528-Customizing-Kintone-with-JavaScript-CSS#System

What happens?
==============

When the specified App has records at a specified Status, then bugs will run accross the screen of Kintone.  
These bugs will only appear for the specified user.  
The more records in that Status, the more bugs will run.
