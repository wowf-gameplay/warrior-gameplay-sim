# WoW Forever Warrior Gameplay Sim

A browser sim for practising the level 60 Fury and Arms Warrior rotations in World of Warcraft: Forever. You press the abilities; the sim auto-attacks a raid boss dummy, tracks rage, stances and cooldowns, and shows a damage breakdown when the dummy dies. Switch between the two specs with the buttons under the tabs.

**Play it:** https://wowf-gameplay.github.io/warrior-gameplay-sim/

## Features

- **Fury (dual wield):** Bloodthirst, Whirlwind, Heroic Strike, Execute, Overpower, Hamstring, Berserker Rage, Bloodrage, Death Wish, Recklessness and Mighty Rage Potion, with Flurry and Ironfoe
- **Arms (two-handed):** Mortal Strike, Overpower, Slam (with a cast bar), Rend, Spearing Strike, Heroic Strike, Execute, Hamstring, Bloodrage, Recklessness and Mighty Rage Potion, with Bloodthrill, Weaponmaster and Two-Handed Weapon Specialization
- Forever's normalized rage, stances with automatic switching, Deep Wounds, Unbridled Wrath, Anger Management and weapon procs
- Toggles for raid buffs, consumables and boss debuffs
- Gear and talent tabs, plus a Stats tab for entering your own character stats
- Rebindable keys (with Shift/Ctrl), adjustable dummy health, and a Warcraft Logs-style end-of-fight breakdown

## Setup

The default gear, enchants and talent builds follow the [MythicSim](https://mythicsim.com/wow-forever/tier-list) DPS Warrior (18/31/2) and Arms Warrior (37/14/0) presets. Mechanics follow the open-source engine MythicSim is built on and Forever beta tooltips, and may change as the beta does. Rend's tick damage is fitted to MythicSim's results, which are well above the tooltip's 147 over 21 sec. Sweeping Strikes has nothing to hit on a single dummy, and the Goblin Sapper Charge and Blackblade of Shahram's proc are not simulated.

## Running locally

It is a single file with no build step: open `index.html` in a browser. Ability icons load from Wowhead's image server, so they need an internet connection.

## Related

- [All sims](https://wowf-gameplay.github.io/)
- [Paladin gameplay sim](https://github.com/wowf-gameplay/paladin-gameplay-sim)
- [Shaman gameplay sim](https://github.com/wowf-gameplay/shaman-gameplay-sim)
- [Druid gameplay sim](https://github.com/wowf-gameplay/druid-gameplay-sim)
- [Rogue gameplay sim](https://github.com/wowf-gameplay/rogue-gameplay-sim)

## Disclaimer

Fan project, not affiliated with Blizzard Entertainment. World of Warcraft is a trademark of Blizzard Entertainment, Inc.
