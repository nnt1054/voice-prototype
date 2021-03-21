# voice-prototype

# hello these instructions only work with OBS Studio for now

# Setting Up:
1. Download the latest .zip release from Github
  * extract contents to a location on your computer
2. Move the photos/gifs you plan to use to the `images/` folder
3. Edit the settings.js file
  * rename the `path` input for each image to your image names
  * adjust the loudness number for each image.  this is the value at which the photos will changes
4. Right Click OBS Studio shortcut > Properties
  * add "--use-fake-ui-for-media-stream" to the end of the Target (example: "C:\Program Files\obs-studio\bin\64bit\obs64.exe" --use-fake-ui-for-media-stream)
  * Apply settings
  * Open OBS Studio using the shortcut
5. Add new Browser Source to your Scene
  * Checkmark Local file setting
  * Browser to where you extracted the voice-prototype contents and select the `index.html` file
 
 probably hopefully should work \o/
