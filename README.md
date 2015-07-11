# Dumatenseb

A version controlled [dwarf fortress](http://www.bay12games.com/dwarves/) world. 

This is an experiment that I'm undertaking for two reasons:

1) I'm kind of perfectionist with this game and I hate losing a single dwarf, and I like having the
ability to roll back time, or branch the entire world in order to try something out, so this is basically my overly
complicated way to save scum.

2) I'm curious to see if a version controlled dwarf fortress save game could result in interesting
collaboration between multiple people modifying a single persistant world that can be synced between players
using git. (PR's to the game world?)

__Try it yourself:__

First you must locate your [Dwarf Fortress save folder](http://dwarffortresswiki.org/index.php/DF2014:Saved_game_folder). For
safety, prior to messing around with anything inside you should probably copy the entire thing to another
location to back it up just in case you mess something up.

To install this world into Dwarf Fortress simply clear the contents of the save folder, and then download
the git repo into your save folder:

```bash
git clone git@github.com:nathanpeck/Dumatenseb.git;
```

Then you can choose a point in time at which to play by checking out a specific commit, or branch. After checking
out a world state in git you need to exit all the way to the main menu of Dwarf Fortress for it to pick up the
changes.

If you want to add on to the repo remember to save the world to offload it to disk, then commit.
