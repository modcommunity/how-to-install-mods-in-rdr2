A guide on how to install **mods** in **Red Dead Redemption 2** (RDR2) on PC, including instructions on how to use a popular mod loader, [Lenny's Mod Loader](https://www.rdr2mods.com/downloads/rdr2/tools/76-lennys-mod-loader-rdr/) (LML)! While focused on **Windows**, this guide includes instructions and tips that should be compatible with other operating systems like Linux.

[RDR2](https://www.rockstargames.com/reddeadredemption2) is an open-world action-adventure game set in a richly detailed late-1800s Wild West, where players follow Arthur Morgan's journey as an outlaw navigating a world of loyalty, survival, and moral dilemmas. Modding RDR2 expands the game's possibilities by introducing new content, improving graphics, enhancing realism, and more which results in a unique gameplay experience!

[**View Guide On TMC (Recommended Due To Better Formatting)**](https://forum.moddingcommunity.com/t/how-to-install-mods-in-rdr2-2025/204)

## Table Of Contents
* [Requirements](#requirements)
* [Backup Your Game Files!](#backup-your-game-files)
* [Where To Download Mods](#where-to-download-mods)
* [How To Install Mods](#how-to-install-mods)
    * [Downloading Mod Drag NPC's](#downloading-mod-drag-npcs)
* [Script Hook](#script-hook)
    * [Downloading & Extracting](#downloading--extracting)
    * [Copy Files From `bin` Folder](#copy-files-from-bin-folder)
* [Lenny Mod Loader](#lenny-mod-loader)
    * [Downloading & Extracting](#downloading--extracting-1)
    * [Copy Files From `ModLoader` Folder](#copy-files-from-modloader-folder)
    * [Launch & Configure Mod Manager](#launch--configure-mod-manager)
    * [Downloading & Installing Mods](#downloading--installing-mods)
* [Conclusion](#conclusion)
* [See Also](#see-also)

## Requirements
* A basic understanding of computer operations such as copying and pasting files from one folder to another.
* A web browser and a basic understanding on how to download files.
* An understanding on how to extract compressed files such as ZIP files using built-in operating system functionality or tools such as [7-Zip](https://www.7-zip.org/).

## Backup Your Game Files!
Before installing mods in RDR2, it is **highly** recommended you *backup* your game files to avoid possible corruption. While most mods are safe, it is better safe than sorry!

You can backup your game files by copying your entire RDR2 game folder.

Here are some file paths where your RDR2 folder may be located.

* If ran through [Steam](http://steampowered.com/), inside of `C:\Profile Files\Steam\steamapps\common`.
* If ran through [Epic Games](https://store.epicgames.com/), inside of `C:\Program Files\Epic Games`.
* If ran through [RockStar Games](https://www.rockstargames.com/), inside of `C:\Program Files\Rockstar Games` or `C:\ProgramData\Rockstar Games`.

Your RDR2's game folder location will most likely vary depending on your game installation and operating system (e.g. Linux will have different paths depending on your Linux Distro).

If you do end up corrupting your game's files, it is strongly recommended you **verify your game's files** through the game launcher (e.g. Steam) or completely reinstall the game.

## Where To Download Mods
You may download mods from places like [Nexus Mods](https://www.nexusmods.com/reddeadredemption2) or [RDR2 Mods](https://www.rdr2mods.com/downloads/). These websites contain many mods and tools!

**NOTE** - We are currently building our own mod workshop and will allow users to upload and download mods in RDR2! Check out our [announcements](https://forum.moddingcommunity.com/c/community/announcements/31) for more information!

## How To Install Mods
While some mods may require different installation methods, it is **generally** very easy to install mods. With that said, I recommend consulting the mod's installation instructions if they provide any.

In most cases, you will be required to **copy** the mod's files to your **RDR2 game folder**.

#### Downloading Mod [Drag NPC's](https://www.nexusmods.com/reddeadredemption2/mods/1386?tab=description)
Here's a quick tutorial on how to download the [Drag NPC's](https://www.nexusmods.com/reddeadredemption2/mods/1386?tab=description) mod from [Nexus Mods](https://www.nexusmods.com) which will act as an example.

Firstly, from the mod's description on Nexus Mods, it must be noted that only **one** version of the mod between *Natural* and *Scripted* should be installed. Otherwise, unexpected bugs will occur. 

After downloading and extracting the mod files, simply copy the files related to the version you want to install to your RDR2's main game folder. In this case, we'll copy the *Scripted* version since this is recommended by the mod creator!

Copy the following files to your RDR2's main game folder.

* `DragPeds_Scripted.asi`
* `DragPeds_Scripted_Config.ini`

Afterwards, launch RDR2 and have fun with the new game feature! Refer to the main mod page if you have any questions or want to know how to activate dragging NPCs.

## Script Hook
Most mods in RDR2 require [Script Hook](http://dev-c.com/rdr2/scripthookrdr2/) in order to operate.

Script Hook in RDR2 is a library that allows native script functions inside of custom `*.asi` plugins. Please note that it doesn't work in multiplayer and Script Hook will forcefully close the game if the player attempts to launch multiplayer.

### Downloading & Extracting
To download Script Hook, go to [this](http://dev-c.com/rdr2/scripthookrdr2/) page and click the **Download** link.

From here, the file should automatically download or you will need to specify where to save the compressed ZIP file.

Next, extract the files from the compressed ZIP file.

### Copy Files From `bin` Folder
After downloading and extracting Script Hook, you will want to copy all files from the `bin` folder to your game directory.

As of this writing, this includes the following files.

* `ScriptHookRDR2.dll`
* `dinput8.dll`
* `NativeTrainer.asi`

After that, Script Hook should be installed! If your game is already running, you will need to restart it.

## Lenny Mod Loader
The [Lenny Mod Loader](https://www.rdr2mods.com/downloads/rdr2/tools/76-lennys-mod-loader-rdr/) (LML) is a popular modding tool for RDR2 that simplifies the process of installing and managing mods. This tool is hosted at [RDR2 Mods](https://www.rdr2mods.com/).

### Downloading & Extracting
Simply download LML from [here](https://www.rdr2mods.com/downloads/rdr2/tools/76-lennys-mod-loader-rdr/?do=download) and extract all files from the compressed ZIP file.

Afterwards, navigate to the extracted contents.

### Copy Files From `ModLoader` Folder
The next step is to copy all files and folders from the `ModLoader` folder to your RDR2's main game folder.

Here is a list of files and folders you will want to copy.

* `ModManager.Core.dll`
* `ModManager.NativeInterop.dll`
* `NLog.dll`
* `vfs.asi`
* `lml.ini`
* `lml` (folder)

After you've done this, the `vfs.asi` file should be in the same folder as the `RDR2.exe` file.

### Launch & Configure Mod Manager
You will want to now launch the mod manager.

Head to the `ModManager` folder from the extracted contents and launch the `ModManager.UI.exe` executable file.

After launching the program, you should see something like below.

![Mod Manager UI](https://github.com/modcommunity/how-to-install-mods-in-rdr2/raw/main/images/lml_mm_main.png)

You will need to configure your game folder by clicking the `...` button in the top-right corner next to the **Game Folder** box. Select your RDR2's main game folder from the File Explorer.

Now save the configuration by clicking the save button located in the middle-*ish* of the screen (this can be hard to miss for some!).

![LML Configure](https://github.com/modcommunity/how-to-install-mods-in-rdr2/raw/main/images/lml_mm_config.png)

**WARNING** - You must keep the Mod Manager open while downloading and installing mods!

### Downloading & Installing Mods
Next, head to [RDR2 Mods](https://www.rdr2mods.com/downloads/) and find a mod you'd like to install. In this guide, we're going to use [Realistic Weapon Overhaul](https://www.rdr2mods.com/downloads/rdr2/weapons/113-realistic-weapon-overhaul/) as an example.

If the mod is supported by LML, you will see a valid **Download with LML** button. Otherwise, the button will be grayed out and say **Download with LML (Unsupported)**.

Next, click the **Download with LML** button and this will attempt to communicate with the LML Mod Manager to download and install the mod.

![LML Web Download](https://github.com/modcommunity/how-to-install-mods-in-rdr2/raw/main/images/lml_web_dl.png)

**WARNING** - You may need to use a different web browser if your current web browser is not supported. [Firefox](https://www.mozilla.org/en-US/firefox/) is the web browser I used in this guide.

Assuming the download and installation went well, the mod should now be installed! You can confirm this by navigating to the **Mods** tab within the Mod Manager as seen below.

![LML Mod Installed](https://github.com/modcommunity/how-to-install-mods-in-rdr2/raw/main/images/lml_mod_installed.png)

Finally, launch RDR2 if you haven't already and enjoy the new content! If the mod(s) you've attempted to install aren't working, refer back to the mod page to check if there additional configuration is required. If you're still experiencing issues, reach out to the mod creator!

## Conclusion
By this point you should have an understanding on how to download and install mods in RDR2. You should also know how to download and install Script Hook along with how to operate Lenny's Mod Loader.

## See Also
* [RDR2 Mod's Wiki](https://www.rdr2mods.com/wiki/)

https://forum.moddingcommunity.com/t/quick-tutorial-steam-deck-getting-script-hook-working-on-rdr2/108

If you have any questions or feedback regarding this guide, please reply to its forum topic [here](https://forum.moddingcommunity.com/t/how-to-install-mods-in-rdr2-2025/204)! This guide will be worked and improved on over time.

Join our [Discord server](https://discord.moddingcommunity.com)!