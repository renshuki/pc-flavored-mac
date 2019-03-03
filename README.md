# PC Flavored Mac

## Why?

The objective of this repo is to help you to get a keyboard mapping on your Mac relatively similar to the one you have on your PC box (Windows or Linux). To reach this goal I use the following software: [Karabiner](https://pqrs.org/osx/karabiner/), [Scroll Reverser](https://pilotmoon.com/scrollreverser/) and [LiteSwich X](http://sysbeep.com/). Beware it's still experimental. 

## What it changes

__Karabiner__ simple key modifications:

| From key      | To key              | Description                                                                              |
|---------------|---------------------|------------------------------------------------------------------------------------------|
| fn            | left_command        | Simulate Windows / Linux <kbd>Ctrl</kbd> key (in case you use your laptop keyboard)      |
| left_control  | left_command        | Simulate Windows / Linux <kbd>Ctrl</kbd> key (in case you use an external keyboard)      |
| left_command  | left_control        | Map <key>Windows</key> key to Mac <kbd>^ control</kbd> key                               |

__Karabiner__ complex key modifications:

_For mac laptop keyboard:_

 * Change <kbd>⌘ command</kbd> + <kbd>tab</kbd> (Mac) to <kbd>⌥ option</kbd> + <kbd>tab</kbd>
 
 > Used to witch between application windows
 
 * Change <kbd>⌥ option</kbd> + <kbd>tab</kbd> (Mac) to <kbd>⌘ command</kbd> + <kbd>Tab</kbd>
 
 > Used to switch between tabs
 
 * Map language input source switcher to <kbd>⌥ option</kbd> + <kbd>shift</kbd>

_For external keyboard:_

 * Change <kbd>⌘ command</kbd> + <kbd>tab</kbd> (Mac) to <kbd>Alt</kbd> + <kbd>Tab</kbd> (Windows / Linux)
 
 > Used to witch between applications windows
 
 * Change <kbd>⌥ option</kbd> + <kbd>tab</kbd> (Mac) to <kbd>Windows</kbd> + <kbd>Tab</kbd> (Windows / Linux)
 
 > Used to switch between tabs
 
 * Map language input source switcher to <kbd>Alt</kbd> + <kbd>⇧ Shift</kbd>

## Setup

### Install Karabiner 
Link: https://pqrs.org/osx/karabiner/

1) Install Karabiner
2) Copy files of this repo into `~/.config/karabiner`
3) Go to *System Preferences > Keyboard > Shortcuts > Input Sources*
4) Map *Select the previous input source* to <kbd>⌥E</kbd> (this is to make the language input source switcher working)
5) Check if bidings appear properly in __Simple Modifications__ and __Complex Modifications__ tabs of your *Karabiner-Elements* app.

### Install Scroll Reverser (optional)
Link: https://pilotmoon.com/scrollreverser/

I use Scroll Reverser to have a reverse scroll on my Mac touchpad but have a reguler scroll when I plug an external mouse.

1) Install Scroll Reverser
2) Go to Scroll Reverser preferences
3) Check the following boxes:
  - [x] Reverse Scrolling
  - [x] Reverse Vertical
  - [x] Reverse Horizontal
  - [x] Reverse Mouse
  - [x] Reverse Tablet


### Install LiteSwitch X (optional)
Link: http://sysbeep.com/

There is a bug/glitch when you move your mouse while doing an <kbd>Alt</kbd> + <kbd>Tab</kbd>.

1) Install LiteSwitch X (no specific configuration)

