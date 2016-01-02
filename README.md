#1pass - 1Password compatbile password management tool for Linux

This is a fork of 1pass from Ryan C. Gordon with some optimzations. Original repository:

http://hg.icculus.org/icculus/1pass/ 

### Building

Use the build.sh script 

### Requirements

*cmake
*libgtk2.0-dev
*libxtst-dev

### Running

Just run the executable with ./1pass, make sure you symlinked (ln -s) your 1password 
keychain folder before.

Press Ctrl + alt + p to trigger 1pass.

### List of changes in this fork:

#### New Activation key (easier for international keyboard layouts)

`Ctrl + Alt + P`
