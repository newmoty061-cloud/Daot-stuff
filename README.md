# DAOT Limbs (addon for Danny's AOT)

Fabric mod, Minecraft 1.21.1, Java 21. Needs Danny's AOT.

- G: shifter heal menu (Arm / Leg / Eyes / Hearts). Bandage: anyone, limbs only.
- Food healing works normally; a shifter's own regeneration is OFF (only Hearts heals them).
- In a titan: hold Shift 5 seconds to smoke away your titan and climb out. In a Colossal, pressing E does it at once with a huge cloud of smoke.
- Cart Titan decay: 4 s -> flesh model, +3 s -> bone model, +3 s -> gone.
- Beast Titan in ice biomes: picks up ice, throws weaker ice rocks, ability #2 carries ice that melts after 2 s.
- First join: you start in a random city of the Paradise dimension (dannys-aot:paradis) with a chest of ODM gear and 4 spare blades.
- First time near a titan: screen shakes, tints red, and you beg in chat.
- Past all the walls of Paradise: ice biome (snow and ice ground).
- Scouts (Paradise only): 100 skins per regiment (Survey Corps, Garrison, Military Police), random personality and name,
  87% Eldian / 10% Ackerman / 3% royal. They talk; sneak + right-click shows who they are. They carry no gear.

Everything tunable: LimbConfig.java. Test commands (op): /daot shifter lose|regrow|limbs|eyemenu ...
- First time you turn into a titan: 10% you control it and are called a master, 90% it will not obey you for 15 s. (/daot shifter firsttransform to test again)
