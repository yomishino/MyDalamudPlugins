# MyDalamudPlugins

Repo listing my FFXIV Dalamud plugins


## Setup Guide

[XIVLauncher](https://goatcorp.github.io/) is required to install and run the plugins.

In the game, open Dalamud Settings,  
and add the URL below to the __Custom Plugin Repositories__ under the "Experimental" tab:
```
https://raw.githubusercontent.com/yomishino/MyDalamudPlugins/main/plugins.json
```

Then install the plugins you'd like to have in Dalamud's Plugin Installer.


## List of Plugins

> :warning: I am not actively working on these plugins at the moment.
> 
> If a plugin listed below has a `[not currently maintained]` tag, then there is no update at all to work with the latest version of Dalamud.
> 
> If it has a `[testing only]` tag, the latest version of the plugin is available only as a testing plugin.
> See [notes below](#notes-on-test-builds) for how to enable getting testing builds.
> Please note there is no guarantee testing builds of plugins will function correctly.

- [ActionEffectRange](https://github.com/yomishino/FFXIVActionEffectRange)  
    provides a visual cue on the effect range of the AoE action the player has just used
- [AetherCompass](https://github.com/yomishino/FFXIVAetherCompass)  
    automatically detects certain objects/NPCs such as Aether Currents nearby and shows where they are
- [TitleRenamed](https://github.com/yomishino/FFXIVTitleRenamed)  
    renames a title displayed on the nameplates


### Notes on Test Builds

The repo may include test builds of the plugins.

Test builds will be listed in the Plugin Installer 
if the "Get plugin testing builds" setting is enabled in Dalamud Settings
(under the "Experimental" tab).

All test builds have "\[TEST\]" appended at the end of the plugin name.

:warning: Please be cautious if you want to install any test build of plugins.
They are unstable and may fail or even crash your game client in some worse cases, for instance.
