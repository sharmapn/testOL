
Two Openlayers maps with different versions, only either shows

This is the repo for the question i posted on stackexchange: https://gis.stackexchange.com/questions/444162/two-openlayers-maps-with-different-versions-only-either-shows

Basically, I have 2 openlayers maps on the same web page. Only one of them shows as importing the css and js libraries related to each map, makes the other one not visible.

I have tried commenting the ol.js and ol.css required for each map, but I have to comment the other. Is there a way I can show both maps on the same page?

I cannot use the second set of ol.js and .css only, as it does not contain one of the functions needed for the first map to show - Please see the error.

I have uploaded the code here. You may need to put on a webserver to run - to prevent the cors error. Code is in the index.html file.

Use Firefox, Click 'Show Map', and press F12 to show map.
