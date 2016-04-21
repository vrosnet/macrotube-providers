# Introduction #

Here is a quick guide to get you going. Close Windows Media Center and all programs before running the installation package. To see user questions or ask a question please use the FAQ [here](https://groups.google.com/d/topic/macrotube-providers-discuss/5rfQVQGnmmM/discussion)


# Details #

The MacroTube Provider Helper is intended to replace the numerous xml configuration files for each video provider in MacroTube, with a version that uses the helper application instead. The Beta will only provide `YouTube/YouTube` HD support, so any of the providers still working with the current xml files will be unaffected.

# `YouTube vs YouTubeHD` #

You no longer need to have both as the Helper has merged these two functionally. So at first an attempt is made to get the HD version of the video - if available. The fall back is then to attempt to locate the MP4 format.

Some videos will still display the old **"Video cannot be display for technical reasons"**. This is usually where none of the formats are suitable for Windows Media Center. Unfortunately, there is no work around for this.

# `MacroTube Configuration` #

By default MacroTube installs the configuration files here:

**`C:\ProgramData\Jasmio\MacroTube\Providers`**

There is an xml file and image per provider.

Note this folder is hidden by default on Windows 7 and you may have to enter the path in the Start menu Run window to find it.

# No thanks, not for me #

If you decide that the helper app is not for you, you can simply  uninstall it.

The app will uninstall itself completely, but the archived xml files in the MacroTube installation folder will need to be copied back manually. There is a date stamped folder **`C:\ProgramData\Jasmio\MacroTube\Providers\Archive_yyyyMMdd`** which will contain the replaced files. Just copy them to the Providers folder.

The archive folder is created only where you choose to automatically archive and copy existing provider files during the MacroTube Helper installation.