# Spell Check Whole Page
Run spell check on all text layers in the page.

Displays a basic panel that allows users to replace the misspelled word or add it to the dictionary, or ignore it.

Uses OSX's built-in spelling features and dictionary to do this.

## The problem
Spell check isn't available for all text layers at a time. If you're using sketch as a replacement for illustrator or inDesign, you really miss the ability to automatically spell check everything everywhere.

## Usage
**To install it, simply [download the zip](https://github.com/ethology-co/sketch-spellcheck-all-layers/archive/master.zip) and double-click the “.sketchplugin” file.** You can access the plugin via the plugins menu. You’ll know its worked when you see the notification at the bottom of the screen.

Here’s a screen capture of the plugin in action:

<img src="images/alert-screenshot.png" alt="Screenshot of plugin's alert">

## Special thanks

Special thanks to

- [Aby Nimbalkar](https://github.com/abynim), who's [select layers of type gist](https://gist.github.com/abynim/04f88d5e4fe47118bfe3#file-sketch-plugin-snippet-select-layers-of-type-js) started me off in creating this plugin
- [Roman Nurik](https://github.com/romannurik) who's [Sketch Nib UI Template](https://github.com/romannurik/Sketch-NibUITemplatePlugin) which provided the framework for the UI

## Next Steps:

There's a shortfall where it will only check each text layer for one misspelled word at a time, so a text layer with more than one misspelled word will only get checked for the first one. I'll work on this for 1.0.

In the meantime, run the plugin multiple times until no mis-spellings are detected.
