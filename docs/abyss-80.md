# Abyss Guides: Floor 80
### Directory
* General Guides
	* <a href="guide-1.md">Starting</a>
	* <a href="guide-2.md">Just Started</a>
	* <a href="guide-3.md">Getting Stronger</a>
	* <a href="guide-4.md">Bossing</a>
	* <a href="guide-5.md">Inheritance</a>
	* <a href="guide-6.md">Medals</a>
* Abyss Guides
	* <a href="abyss-60.md">Floor 60</a>
	* <a href="abyss-65.md">Floor 65</a>
	* <a href="abyss-70.md">Floor 70</a>
	* <a href="abyss-75.md">Floor 75</a>
	* **Floor 80**
	* <a href="abyss-85.md">Floor 85</a>
	* <a href="abyss-90.md">Floor 90</a>
	* <a href="abyss-95.md">Floor 95</a>
* Equipment Data
	* <a href="list-weapons.md">List of Weapons</a>
	* <a href="list-armours.md">List of Armours</a>
	* <a href="list-names.md">Weapon Names</a>
* Reroll Suggestions
	* <a href="reroll-1.md">Knight</a>
	* <a href="reroll-2.md">Black Mage</a>
	* <a href="reroll-3.md">White Mage</a>
	* <a href="reroll-4.md">Thief</a>
	* <a href="reroll-5.md">Ranger</a>

### Table of Contents
* [Dragon Twin Princess (Dual Bosses)](#dragon-twin-princess-(dual-bosses))
* [Overview](#overview)
* [Threshold/Pattern](#thresholdpattern)
	* [Moves](#moves)
* [Tips](#tips)
	* [Knight](#knight)
	* [Black Mage](#black-mage)
	* [White Mage](#white-mage)
	* [Thief](#thief)
	* [Ranger](#ranger)
* [Clear videos](#clear-videos)
* [References](#references)


# Dragon Twin Princess (Dual Bosses)
![Boss](https://caelum.s-ul.eu/Muyv7ce4.jpg)
* Dragon Light Princess - <img src="https://caelum.s-ul.eu/hLKNs6KH.png" width="25"> Earth/Dragon/Physical
* Dragon Shadow Princess - <img src="https://caelum.s-ul.eu/hLKNs6KH.png" width="25"> Earth/Dragon/Magical
* HP: 647,080 each
* Debuffs: Blind, Bind, Waste, Stop, Bleed

# Overview
* The hardest boss in BDFE of all times.
* The two bosses buff / cleanse each other as well as dispel your buffs in thresholds.
* They spam lethal and non-lethal attacks individually. 
* They change phase individually every 130k HP.
* Due to the way bosses knock you around, default row is the middle. 
* Positions are important so that two healers / knight do not die at the same time.
	* Usual order: White Mages/Knights take 2, 3; Rangers/DPS take 1, 4.
* They must be defeated at the same time, otherwise
	* The surviving sister will heal herself back to full HP
	* The dead sister will be revived with slightly lower HP

# Threshold/Pattern
## Moves
* Permanent blind field.
* Regular attacks
	* Light: Waste, knockback 1 tile, dispel 1 buff
	* Shadow: Bind, knockfront 1 tile, dispel 1 buff
* Whole party attacks
* Row red tiles (lethal from 130k onwards)
* 2-row red tiles
* Lethal single tiles (to 390k)
* Lethal three tiles
	* Target tile and two tiles beside it
	* If positioned 2, 3, only two tiles

Light/Shadow Princesses will do the following actions when they change phase. They change phase separately. For example, both will happen concurrently if both change phase at the same time.

Note that the exact buff/dispel/cleanse timing is as follows: if one sister crosses the threshold, and the other sister finishes her current action. For example if light sister crosses 520k while shadow sister is casting a nuke, buff/dispel will happen when shadow sister finishes casting, regardless of what light sister is doing.

HP | Light | Shadow
--:|---|---
520,000 | Dispel party buffs | Cleanse Light debuffs
390,000 | Cleanse Shadow debuffs | Dispel party buffs
260,000 | Dispel party buffs  | Cleanse Light debuffs
130,000 | Dispel party buffs  | Dispel party buffs

They start with Brave 1 / Default 1 on both of them. Then, each of them buff both herself and her sister whenever either of them changes phase. They change phase separately. For example, both will happen concurrently if both change phase at the same time.

HP | Self | The Other
--:|---|---
520,000 |  Default 2 | Brave 2
390,000 | Default 2 + Regen 1 | Brave 2 + Agility
260,000 | Default 3 + Regen 1 | Brave 3 + Agility
130,000 | Weakness 3 | Brave 3 + Default 3 + Agility + Fastcast 2 + Regen 2

# Tips
* Bind immunity is required for all.

## Knight
* AoE Taunt is required.
* Regen 2, HP Up buffs help.
* Job is to stay alive while Rangers extend taunt.
* Be mindful of their debuff clear timings.
* Typical to auto buff Pdef/Mdef with Keysword.
* If enough auto power, auto heal helps.
* Try to have waste / bleed resistance.

## Black Mage
* Fastcast and resist buffs help.
* Either blind immunity or levitate.
* One of them has lower Mdef
	* Concentrate 2 without Split like Chocobo/Bleach makes job easier
	* Alternate ST and AoE to adjust HP
* Try to have waste / bleed resistance.

## White Mage
* Multi-row special/auto help when you are baiting or others are. 
* Be mindful of HP timing to reapply buffs. 
* Be aware of red markers when casting specials. 
	* Don't kill yourself or others.
	* You may tend to miss revives due to knockback/front.
* Cleanse waste or bleed as soon as possible.
* Prioritize BP feeding especially if there is only one ranger.
* Try to be aware of Ranger's dispel bow reload.

## Thief
* Blind immunity or 100% aim dagger.
	* i.e. Twilight or Glitzy
* Try to have waste / bleed resistance.

## Ranger
* Prioritize Slow and Slowcast.
* For double rangers, try to have slow 3.
	* Try to have earth BP/reload for Nether Bull.
	* Typical mono earth build: 
		* Nether Bull, Dragon Slayer
		* Royal (may not be required if partner has Glitzy)
		* Forceless 2 (Sakura/Euclid/Greed)
		* 3* Slowcast 1 / Spiritual / Nier / Octopath
	* Typical non-slow 3 build:
		* Glitzy (or other dispels)
		* Nether Bull/Tanabata
		* Slow 2 (Compass/Love/Dragon Slayer)
		* Twilight (or equivalent)
		* 3* Slowcast 1 / Forceless 1 / whatever
* Solo ranger is much more challenging.
 	* Typical build: 
		* Glitzy (may need 2 dispels if otherwise)
		* Slow 2 (Compass/Love/Dragon Slayer)
		* Nether Bull/Tanabata
		* Twilight (or equivalent)
		* Phoenix / 3* Slowcast 1 / Forceless 2
 	* Depends on the set up, need extreme BP builds.
* Be mindful of HP timing to dispel / reapply debuffs.
	* Dispel Brave as soon as possible.
* If there is no DPS, having Mono Wind Set helps immensely to clear faster as well as to easier finish both sisters at the same time
	* Typical mono wind build:
		* Glitzy, Legend / Twilight, Quartz, Cupid
		* Harp / Candy / Limited for extension
		* Cutlassfish Bow if slot still available

# Clear videos
* <img src="https://caelum.s-ul.eu/6ep5gyBy.jpg" width="25" alt="Priest"><img src="https://caelum.s-ul.eu/KHPaHS9n.jpg" width="25" alt="Sniper"><img src="https://caelum.s-ul.eu/KHPaHS9n.jpg" width="25" alt="Sniper"><img src="https://caelum.s-ul.eu/6ep5gyBy.jpg" width="25" alt="Priest"> https://youtu.be/23Zyk5sG494
* <img src="https://caelum.s-ul.eu/6ep5gyBy.jpg" width="25" alt="Priest"><img src="https://caelum.s-ul.eu/KHPaHS9n.jpg" width="25" alt="Sniper"><img src="https://caelum.s-ul.eu/Fi8dYRtv.jpg" width="25" alt="Assassin"><img src="https://caelum.s-ul.eu/wIBPnCMQ.jpg" width="25" alt="Paladin"> https://youtu.be/pp3D3XaKiaA
* <img src="https://caelum.s-ul.eu/6ep5gyBy.jpg" width="25" alt="Priest"><img src="https://caelum.s-ul.eu/fNKzRReH.jpg" width="25" alt="Arcanist"><img src="https://caelum.s-ul.eu/KHPaHS9n.jpg" width="25" alt="Sniper"><img src="https://caelum.s-ul.eu/6ep5gyBy.jpg" width="25" alt="Priest"> https://youtu.be/-4F5ECVmKxk
* <img src="https://caelum.s-ul.eu/6ep5gyBy.jpg" width="25" alt="Priest"><img src="https://caelum.s-ul.eu/KHPaHS9n.jpg" width="25" alt="Sniper"><img src="https://caelum.s-ul.eu/fNKzRReH.jpg" width="25" alt="Arcanist"><img src="https://caelum.s-ul.eu/wIBPnCMQ.jpg" width="25" alt="Paladin"> https://youtu.be/kCrr7-exzWk

# References
* [BDFE攻略情報局](https://wiki3.jp/bdfe-istantal/page/221)