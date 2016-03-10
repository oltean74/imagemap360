# imagemap360
Responsive panoramic image map
#Image map 360 by Ioan Oltean.
Embed interactive Panoramic Image Map on your site with this simple plugin.

## Compatibility
Modern browsers such as Chrome, Firefox and Opera on both desktop and smartphones have been tested. Some issues on some native android browsers.

## Basic Usage
 See index.html structure for basic usage.

````javascript
   $("img.your-image-class").imagemap360({
...options here...

});

##Available options
viewport_width: 600      //Width in pixels; default is double size of your image height
control_display: 'auto'  //'auto' option: controls will auto hide after 10 sec 
                          //'yes' option: controls will never hide
start_position: 10       //number representing start position of image measured in pixels; must be between 0 and your image width value
auto_start: true         //the image will play automatic on window load, otherwise choose false
mode_360: false          //the image will be animated on it's width limits; 
                          //mode_360:true-the image will play forever unless an event ocur( ex. click,touch)

##Tip
For great presentaions can be used toghether with other plugins like colorbox, fancybox or tooltip plugins.

