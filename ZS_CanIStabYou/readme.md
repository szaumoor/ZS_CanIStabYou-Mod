# Introduction

## Can I stab you?

That's the million-dollar question for every character who can backstab.

This mod addresses in a very modular way your preferences as far as who gets to be immune to backstabs. It's a common complaint that we don't get to backstab many enemies, including many in ToB, which reduces the already underpowered (and seemingly hated by Bioware) Thieves (especially single-classed), where backstabs are one of the main and sometimes **only** way of excelling and contributing majorly in combat. They will generally be outplayed by Fighters and other classes that can be "left alone to do their thing in combat" without micromanagement. Micromanagement should pay off more than it does.

There's a group of components to remove backstab immunities from particular types or specific enemies, and a group to enforce this immunity as per your liking.

## What is a backstab?

There seems to be **schools of thought** around what a backstab should be. A backstab should be either:

- **(A)** Similar to a critical hit, it's just a hit that is dealt on a weak point -- or any other point that hurts and damages badly or cause important structural weakness of the creature.
- **(B)** Unlike a critical hit, it's not about weak points, but about attacking by surprise or otherwise without seeing it coming, and the surprise is what makes the hit they take so powerful.
- **(C)** It's both, it's surprise attack that hits a weak point that otherwise would be difficult to hit if the creature was completely aware of your existence.
- **(D)** It doesn't matter and I don't care, I just want Thieves to be f***ing useful. Everything can be backstabbed, so shut up.

Followers of school of thoughts (A) would argue that if a creature has weak points or structural weaknesses, backstabs are fair game, regardless. So a celestial with higher awareness can be backstabbed, because it has a body with parts that can be damaged independently -- some of them being more important than others. Golems are fair game too because there are constructs that can have chips on their armor, but things like slimes and phantasmal creatures would not apply.

Followers of school of thought (B) would argue that if a creature has higher awareness, such as a celestial being or a demon, they wouldn't be able to be backstabbed, but other things that can be surprised are fair game.

Followers of school of thought (C) would argue that if a creature has either higher awareness or no weak points, they cannot be backstabbed under any circumstance.

And followers of school of thought (D) are just sick of Thieves being useless and just want to have fun with engaging gameplay regardless of whether it makes earthly sense or is lorewise accurate in some version of the setting.

I personally follow the school of thought (A): similar to sneak attacks, if a creature has a non-amorphous, completely physical body, then it can be backstabbed, even if it has higher awareness and can't be made unaware of your existence through invisibility. If they are distracted, they can be considered unaware in the sense that they may be dealing with something else. For example, maybe another enemy is fighting it, or they're otherwise distracted. I resent the idea that seeing the invisible implies that they cannot be backstabbed, and I think it's cheesy and implemented poorly.

**What is your school of thought?**

I know, right? Completely necessary section of the mod's readme.

## Components

### Backstab Immunity: Removals

**Component 99:** Everything can be backstabbed

This component is mutually exclusive with the rest of components in this group since it covers everything already.

**Component 106:** All humanoids can be backstabbed, except ToB bosses  
**Component 102:** Humanoid ToB bosses can be backstabbed  
**Component 107:** Gromnir can be backstabbed  
**Component 103:** Yaga-Shura can be backstabbed  
**Component 112:** Sendai can be backstabbed  
**Component 122:** Balthazar can be backstabbed  
**Component 113:** Abazigal can be backstabbed (human form)  
**Component 114:** Abazigal can be backstabbed (dragon form)  
**Component 105:** Amelyssan can be backstabbed  
**Component 121:** Bhaal's avatars can be backstabbed  
**Component 100:** Beholders can be backstabbed  
**Component 115:** Celestials such as Planetars, Devas, and Solars can be backstabbed  
**Component 117:** Demogorgon can be backstabbed  
**Component 116:** Demons and devils can be backstabbed (except Demogorgon)  
**Component 109:** Demiliches can be backstabbed  
**Component 110:** Dragons can be backstabbed  
**Component 101:** Golems can be backstabbed  
**Component 104:** Minotaurs can be backstabbed  
**Component 118:** Liches can be backstabbed  
**Component 108:** Slimes can be backstabbed  
**Component 120:** Mist creatures can be backstabbed  

### Backstab Immunity: Enforcement

**Component 201:** All spectral undead are immune to backstab  
**Component 205:** All golems are immune to backstab  

### Invisibility Detection: Removals

**Component 300:** Every creature marked as able to see through invisibility is automatically immune to backstabs (version 2.6+)

Creatures before game version 2.6 are automatically immune to backstabs, the logic being that if they can see through invisibility, the backstabs cannot trigger as you are effectively not invisible as far as they're concerned. This ensures any creatures marked as able to see through invisibility are immune to backstab if playing in game versions 2.6+, where the previously mentioned behavior is not present.

**Component 301:** No creature can see through invisibility, they must rely on invisibility dispelling like any other  
**Component 302:** Dragons cannot see through invisibility, except Abazigal  
**Component 303:** Demons cannot see through invisibility, except Demogorgon  
**Component 304:** Celestials cannot see through invisibility  
**Component 305:** Liches cannot see through invisibility  
**Component 306:** Demiliches cannot see through invisibility  
**Component 307:** The Unseeing Eye cannot see through invisibility  
**Component 308:** Sendai cannot see through invisibility  
**Component 309:** Balthazar cannot see through invisibility  
**Component 310:** Yaga-Shura cannot see through invisibility  
**Component 311:** Amelyssan cannot see through invisibility  
**Component 312:** Abazigal cannot see through invisibility  
**Component 313:** Demogorgon cannot see through invisibility  
**Component 314:** Bhaal's avatars cannot see through invisibility  
**Component 315:** Rune Assassins cannot see through invisibility  

## Compatibility and issues

Bear in mind that in game versions previous to 2.6, creatures with invisibility detection via script (balors, dragons) can't be backstabbed either, as it is implied that because they can see through invisibility, your character is as far as they're concerned effectively not invisible and thus you cannot backstab them. Personally, I think it's not quite logical. Higher awareness doesn't mean it's impossible to be distracted and therefore susceptible to a big surprise hit. In the end it's just a poorly implemented feature as far as I'm concerned.

In 2.6+, more control is available, and only those that have the backstab immunity opcode are indeed immune. This means that in versions < 2.6, these components will not open those enemies to backstabs just with the backstab immunity removal components and thus invisibility detection via script must be removed too.

I might add components in the future for critical hit immunity for the benefit of those who see backstabs and critical hits as essentially equivalent in terms of what gets affected by critical hits and backstabs.

## Acknowledgements and credits

Everyone on Discord and G3 for ideas and general help.
