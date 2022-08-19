# GRAND STORY: SiIvagunner music mod for Cave Story for 3DS

The highest quality BGM for Cave Story for 3DS (the original version, not the "Cave Story 3D" remake). Works on jailbroken 3DSes as well as with the Citra emulator. Port of the original PC mod by [Squaggies](https://forum.cavestory.org/threads/grand-story-music-mod-siivagunner-tribute.13728/).

## Installation

1. Download the latest release.
2. Unzip the folder. You'll get a folder named "000400000009B300" (This is the Game ID of the American version)
3. 
    * a. For Citra: 
    
    Open Citra, right-click on your Cave Story ROM and choose "Open Mods Location" then put the `romfs` folder from inside the extracted folder into that location. All in all, the path to the sound files should read `[YOUR CITRA FOLDER]\user\load\mods\000400000009B300\romfs\org\access.org` etc. (the number will be different if you don't have the US version of the game).

    * b. For jailbroken 3DS: 
    
    Put the `000400000009B300` folder into the `\luma\titles\` directory of your 3DS SD card. If you don't have the US version of the game, change the name of thee `000400000009B300` folder accordingly:
- Europe:	`0004000000098900`
- Korea:	`00040000001A5500`
- Japan:	`0004000000179A00`
(So the path of the audios will look like `\luma\titles\000400000009B300\romfs\org\access.org` etc.)

That's it. If you did everything right, you should hear a GRAND variation to the title theme right on the title screen. To deactivate the mod, just rename the respective folders to anything else! Or deactivate single tracks by changing their names, e. g. to `access.org_deactivated`.
