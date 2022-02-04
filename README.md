This patcher (named **"tellipatch"**) will fit a Japanese .hack//Frägment ISO with the latest (work-in-progress) .hack//Frägment translation!

You should only use this patcher with an ORIGINAL .hack//Frägment ISO.

You may receive checksum errors if you try to use it with a modified ISO.

----------------------------------------------------------------

## **Links & Downloads:**

Required (Windows Only): [ImgBurn](https://www.imgburn.com/index.php?act=download)

Required (Windows Only): [.NET 5.0 Runtime](https://dotnet.microsoft.com/download)

[Patch Notes](https://zerobin.net/?344b60ffcc76151e#FLbf7PjvHy+lJHm45MiykdLsxApHPxZ7PkS4w49vOqI=) *(last updated: 2022 January 19)*

[Video Guide](https://www.youtube.com/watch?v=8yehreqjD0M)

----------------------------------------------------------------

## **How to use this patcher:**
1. Put your (unmodified) Japanese.hack//Frägment ISO in the same folder as the batch script (Apply Patch.bat).Rename this ISO "fragment.iso".
2. Run the "Apply Patch" batch script. This does a few things, all automatically:
- mounts the ISO to your PC
- copies all the data from the ISO to a local directory
- patches the local directory with the translations
- rebuilds the ISO using ImgBurn

Please follow each prompt very closely until you reach the end.

Once the patcher is finished, you can find your new game / ISO alongside the rest of the patcher's files, named "dotHack Fragment (1.3).iso".

As progress is made on our end, updates are automatically pushed directly to you. It's recommended you routinely run Apply Patch.bat to make sure you have the latest translations applied to your game / ISO.

----------------------------------------------------------------

## **F.A.Q.**
## **What exactly IS tellipatch?**
tellipatch is a community collaboration with the ultimate goal of creating a comprehensive .hack//frägment english translation. this script combines the translations from Princess Alice's patch, Vi Ness's patch, Emuz's graphical patch, and PLM's patch and builds them all into one functional ISO.

## **ImgBurn fails to run when I'm patching!**
Chances are you have installed ImgBurn in a location other than the folder "Program Files (x86)". You can change this line in the batch script:
[quote]"PATH TO IMGBURN\ImgBurn.exe" /MODE BUILD /SRC "fragment_eng\" /DEST "%CD%\dotHack Fragment (1.0).iso" /START /OVERWRITE YES /ROOTFOLDER YES /CLOSESUCCESS[/quote]

## **The patcher errors out saying "The file or dictionary is corrupted and unreadable."**
Your ISO is already modified, this is a common error if you accidentally try to patch the Coldbird version. The only thing I can legally tell you is to try ripping your own copy directly from the game disc.

## **The patcher closes unexpectedly before completing and I can't read the error message!**
Your Antivirus is blocking one of either "xdelta.exe" or "fragmentpatcher.exe". Disable your AV temporarily or add these exe's to your exceptions.

## **The patcher will only continue on to the next step if I press enter after each prompt!**
You may have clicked somewhere inside the cmd prompt window, causing it to enter "Mark Mode". In this mode, the cmd prompt freezes the output window to make highlighting text / copy & pasting easier. To disable this mode, right click the cmd prompt's title bar, and select Properties. Uncheck "Insert Mode" and "Quick Edit Mode", then click OK to save.

----------------------------------------------------------------

## **Screenshots:**

![https://i.imgur.com/0KPPHzRl.png](https://i.imgur.com/0KPPHzRl.png) ![https://i.imgur.com/ZJs8IKal.png](https://i.imgur.com/ZJs8IKal.png)
![https://i.imgur.com/ulMqboul.png](https://i.imgur.com/ulMqboul.png) ![https://i.imgur.com/B5w5DSVl.png](https://i.imgur.com/B5w5DSVl.png)
![https://i.imgur.com/60SHWfdl.png](https://i.imgur.com/60SHWfdl.png) ![https://i.imgur.com/8ZGQnKIl.png](https://i.imgur.com/8ZGQnKIl.png)


----------------------------------------------------------------

Credit to PLM, Princess Alice (Telli), Dau, Emuz, Enlike, Nyao, Vector, Vi Ness, Xithyl_kykori, and Zackmon.

Special thanks to 1UP, Alkalime, Bison, Dash, Erroneous, Esor, Falions, Harrito, NCDyson, rlstine, Snownami, Robert Coldbird & the Netslum community.
