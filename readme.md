# Nev's Gaming System

The aim is to make an interface, similar to Steam's Big Picture Mode, that is store agnostic, thus being able to handle collections from multiple sources like locally installed, game store interfaces such as Steam, Lutris and Heroic (initially. Likely there'll be more to come), Bottles and various emulators. The user should then be able to define smart groups (put all of the games from this emulator under this category or put all of the games which have the words "Prince of Persia" into a prince of persia category and sort them by release date etc.) and be able to launch games from a controller based interface.

Ultimately, the goal is to have a "console" like system that can be plugged into a network and used to play games on any device within the network via sunshine. So via Android TV boxes, phones, tablets etc.

Initial work is on scripts to search a system for games and export such lists for use by Pegasus Frontend as well as download any artwork and game descriptions. BUT I'd like to be able to extend Pegasus' abilities to be able to, for example, install a game in Steam if it's available in the user's library but not yet installed. So eventually probably a fork of Pegasus Frontend to add the ability to add submenus/context menus.

All of the code here is released under GPLv3.