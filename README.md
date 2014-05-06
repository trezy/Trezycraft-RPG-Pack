# Trezycraft

Trezycraft is a library of Denizen scripts intended to prevent Minecraft server admins from reinventing the wheel. How often have you needed to build a new script to make your NPCs go to bed at night? Or drop loot when mobs are killed based on a weighted drop system? Or create random bosses in the world?

Trezycraft aims to fix all of that by providing a standard library of Denizen scripts that can be extended to customize your Minecraft world.

## How this project works

Trezycraft utilizes [Denizen](http://wiki.citizensnpcs.co/Denizen) to provide a collection of scripts to use as frameworks for more advanced scripts. This way you can simply extend an NPC base type or Quest base type rather than building the whole script from scratch.

### Denizen

Denizen is a [Bukkit](https://bukkit.org/) plugin that relies on [Citizens 2](http://citizensnpcs.co/) and provides a robust scripting language based on YML to allow the creation of powerful, extensible scripts to modify your world. Trezycraft is written entirely in the Denizen scripting language, dScript.

### Organization

Trezycraft is organized into modules to allow abstraction and encourage reusable code.

## How to use this project

Download
/denizen reload scripts
???
Profit!

## Meet the modules

### Core

### Loot