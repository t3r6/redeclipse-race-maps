# Red Eclipse community Time-trial (Race) maps pack v1.2

I decided to pick up this mappack by TristamK and add some additional maps. 

The mappack version is updated to v1.2.

Most maps are only compatible with RE 1.3 and some with Blue Nebula (RE 1.6 fork).

### Run a map

1. Open game console with:

```
tilda (`)
```

2. Type:

```
trial map_name
```
or

```
race map_name
```
Increase time limit for hard maps
```
timelimitrace 25
```
Spectate and increase game speed for spectating fast
```
spectate 1
gamespeed 300
```

### Tutorial maps

- `tuto` by `Bonifarz`. This map is highly recommended in the first place to learn basic and advanced tricks.
- `tutorial_v0.1` and `tutorial_v0.2` by `Bonifarz`.

### The hardest maps

- escapeultima
- iwbte
- crueldozen
- port
- euphoria

### Maps with changed physics

- reaction
- df_ciy-normal

### Notes

If you want your maps to be listed under a particular gametype, add them to `config/version.cfg` (`/share/blue-nebula/config/version.cfg` in Blue Nebula).

For example `sv_racemaps "map1 map2 ..."`.`

### New added maps and fixes

vast 2<br>
vertigo-jump_v1.1.5<br>
trespass_v2.1 - fixed skybox<br>
Bonifarz mappack<br>
crueldozen_0.2 - some sections are a bit different than that of 0.3<br>
crueldozen_0.3<br>
crueldozen_bn (with fixed pic) - (Blue Nebula edition) the version used on the Rennstrecke race server (cruelDozen_0x3d53c85b)<br>
tonatiuh_v1.1c - a bit more difficult version than the final tonatiuh (mapmusic is fixed). Secret passages are also different in this version.<br>
twisted_0.3<br>
practice-jump<br>
amplification_beta the version before it was included to 1.4.5<br>
absorption_beta<br>
official 1.6 race maps<br>
official 2.0 race maps<br>
official race maps removed from 1.6 but present in RE_1.4.5<br>
minerange - not a trial map but with very original gameplay<br>
Added screenshot for jumpstatic by Goku<br>
escape_sp_final - this is a singleplayer map version with a secret section and custom sounds<br>
escape_sp_v1<br>
escapeeasyfinal - the map version with hoops<br>
escapehard_v1<br>
iwbte_bn - (with fixed pic) - (Blue Nebula edition) the version used on the Rennstrecke race server (iwbte_0x4ea8d6a9)<br>
sphierpinski<br>
carve<br>
exotic 1.2 - skybox fixed<br>
ladderrace - skybox fixed<br>
inverted - skybox fixed<br>
testroom3_v1.0<br>
reservoir (2 versions) - fixed<br>
escapeultima<br>
SniperGoth mappack with small fixes<br>
tutorial_v0.1 and tutorial_v0.2<br>
tlp_tutorial_v1.0 and tlp_tutorial_v1.1<br>

### Issues
!!! All the custom trial maps go with the 'edit' tag and not 'race'. It means that you don't see a custom race map under a race section. Can it be fixed?<br>
Check all final checkpoints types<br>
Check rotating objects<br>
Delete cfg redundant info<br>
Add txt<br>

hawk - missing skybox (it uses old skybox from RE_1.4)<br>
Reaction - the map cannot be played. You are getting stuck in the spectator mode. (The map is playable and can be finished in RE_1.4) - the fix is ready but not implemented yet<br>
polarization - missing skybox and some textures, the ceiling is clipping at the end of the map so that allows to change a route and break the map due to the wrong sequence. This singleplayer map can as well be played in Race.<br>
jumptastic - very cool map but there is a checkpoint that spawns you right at the death trigger and you get stuck on the map if die. So I think that issue is critical.<br>
relax_v0.3 - no checkpoints to restore impulse meter
<br>
iwbte_v1.1 - console error unknown command setpixelparam<br>
escapehard_v1 and escapehardfinal<br>
fan in the first room does not spin like in the vid: https://www.youtube.com/watch?v=-4B6fyIQdwk&t=39s<br>
texture error in escapehard_v1<br>
ambient sounds are too loud<br>
checkpoints do not work in escapehard_v1<br>
console error unknown command setpixelparam error in escapehard_v1<br>
there is a planned secret room in the escapehard_v1 version which was removed in the final version<br>
(it would be nice to have this section restored - can be taken from the SP final version and modified)<br>
sphierpinski - this could have been of great potential as a unique and interesting race map but it has a lot of issues like unstable starting point; it's not clear where to go; strange checkpoints: the layout is very simple and dull (you just go from the red base to the blue base). This map should be completely reworked as a race map. I think the music from tonatiuh will perfectly suit it.<br>
setpixelparam. https://forum.freegamedev.net/viewtopic.php?f=73&t=3393<br>
<br>
escape_sp_final<br>
escape_sp_v1<br>
escapeeasyfinal<br>
ambient sounds are too loud<br>
console error unknown command setpixelparam<br>
The RE map music should NOT be present on the map since the maps use their own music<br>
escape_sp_v1 has an unfinished secret section<br>
the secret room cannot be accessed in other version like shown in the video: https://www.youtube.com/watch?v=el4FtbzspkE<br>
ghostcity - hoops do not work (this is how it should look like: https://www.youtube.com/watch?v=_GbW7D2m2j4); console error unknown command setpixelparam; checkpoints work but there is some strange duplications.<br>
escapeultima - missing logo banner<br>

### Improvements could be done
Map name patterns. Should all the maps' names be written in the small letters?<br>

airtortures, lavatortures, sinai - these are cool fast speedrun maps if you break them and use shortcuts. Hard version of these maps are welcome.<br>
airtortures - one can make a huge shortcut which makes the map very easy.<br>
lavatortures - there is no teleport to the finish at the end of the map.<br>
sinai - there is a shortcut that cuts the map in a half right from the start or you can easily jump to a finish window from the below platform in the middle of the map.<br>
hawk - there is a shortcut near the rings that can be improved, shown here: https://www.youtube.com/watch?v=50AL_l0azW4<br>
Reaction - the map is very interesting but it has some weird custom physics. It was meant to be so: https://forum.freegamedev.net/viewtopic.php?f=73&t=3886. It'd be nice to have a version of this map with the standard physics. I tested it with the normal gravity and it still does not feel right because the map was scaled for this physics. So a remake with standard physics is welcome.<br>
waterrunlow - the FPS on this map is incredibly low which makes it unplayable. The map is not fully complete and it should be optimized.<br>
waterrun - is even worse than waterrunlow in terms of FPS drops. It should be optimized or else it's not playable.<br>
carve - you can get stuck at the end of the map near the vertical water pool<br>

## Map that are fully compatible with 1.6
Everything will be retested once the archive is ready.

### Original description by TristamK

Custom Map pack compiled by TristamK, for all who like Time-Trial in game Red Eclipse on 28-07-2013
Most of the maps (70%) in this pack are made by Me, 40-65% of maps by others ppls somehow modified by Me. Also 80% of my maps improved very much and most of bugs fixed

| Total maps | 207 |
| ---------- | --- |
| Tristamk | 108 (9 maps will be added in additional map pack or later) |
| Temka | 32 |
| Goku | 3 |
| h1q1 | 4 |
| Michel | 15 |
| other | 14 |
| speedmapping | 27 |
| RESMC | 4 |
-------------------------
Maps sorted in folders by Name of creator.

Installation Instructions
 -------------------------
 To Install, just place the maps from folders in your Red Eclipse\maps\ folder.
 or what ever folder, where you have your custom maps 
On Windows: C:\Users\<YOUR USERNAME>\Documents\My Games\Red Eclipse
Remember to add the maps to your server config file, if you run a server



All files,stored in the folders "TristamK" and "SpeedMapping",  made by Kirill Kolesnikov aka TristamK (TristamK@bk.ru) , is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License.

To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/
 