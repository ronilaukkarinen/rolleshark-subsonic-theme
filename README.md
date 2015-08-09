RolleShark
=========================

Designed to be the most beautiful Subsonic theme in the world.
--------------

**Plese note:** This theme is not designed to be responsive and will not be because of the structure of the original Subsonic webview. For tablet and mobile use I recommend [Jamstash](http://beta.jamstash.com/), [Dsub for Android](https://play.google.com/store/apps/details?id=github.daneren2005.dsub&hl=en) and [iSub for iOS](https://itunes.apple.com/en/app/isub-music-streamer/id362920532?mt=8).

![Screenshot (Subsonic powered by Fluid App)](https://raw.githubusercontent.com/ronilaukkarinen/rolleshark-subsonic-theme/master/screenshot.png "Screenshot")

A very quick yet functional Subsonic theme based on Sonic and inspired by Grooveshark UI. Icon-edits and CSS by me.

Code may be crappy, because was forced to use pseudo-selectors and other half-witted gum, because I wanted to respect the function of Subsonic themes by not touching the backend even it frustrates me that it consists mostly of old school HTML code (=tables). But it works and that's all that matters. Because of the old backend, there won't be a responsive version. For mobile, use Android/iPhone apps or [Jamstash](http://jamstash.com).

Contains a lot of advanced CSS3, therefore works best on latest Google Chrome. Coded entirely using Linux command line editor nano :-)

Prequisites
--------------

- Subsonic / musiccabinet
- Sonic White -theme

Installation (Linux)
--------------

git clone this repository, navigate to folder (`cd /path/to/files`) and then input this command (I presume you have Musiccabinet 0.7.24c installed, otherwise please correct the version number in the command):

**Note: Might override other theme files, so use with care!**

##### Subsonic (Vanilla) 5.2.1:

1. Run `sh install_vanilla.sh`
2. Kill subsonic process and start it again
3. Go to Settings and apply RolleShark

##### MusicCabinet 0.7.24c:

1. Run `sh install_musiccabinet.sh`
2. Kill subsonic process and start it again
3. Go to Settings and apply RolleShark