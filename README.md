# GTA BORS Brothers

Two cops. One city. Zero rules.

A top-down GTA-style game that runs in the browser. Pick your brother, MaFl or BARY, and take on Bors City alone or with the rest of the family.

**Play here:** https://YOUR-USERNAME.github.io/gta-bors-brothers/

## Game modes

**Solo:** The full city on your own. It works without an account or any setup.

**Free roam (3 to 5 players):** One shared city with traffic, gangs, cops, missions and a wanted level. You can switch friendly fire on or off in the lobby.

**Deathmatch:** Players only, 4 minutes, most kills wins.

## How to play together

1. One person opens the game and clicks **Create room**.
2. Click **Copy invite link** and send it to the others.
3. Everyone opens the link, picks MaFl or BARY and clicks **Join room**.
4. The host picks a mode and clicks **Start**.

In free roam the host's browser runs the city. The host should play on a laptop and keep the game tab in front.

## Controls

**Mouse (default on desktop)**
- Hold the left button to walk toward the cursor. The further away the cursor, the faster you go.
- Right button or Space shoots.
- Click a car to walk over and get in.
- In a car: hold the left button to drive toward the cursor, right button to brake and reverse, Space to drift, E to get out.

**Keyboard** (switch in Settings)
- WASD moves, Shift walks.
- E gets in and out of cars.
- 1 to 4 or the mouse wheel switches weapons.
- Esc opens the menu.

**Phone**
- Left thumb moves or drives.
- Right thumb: hold to shoot with auto-aim, or drag to aim yourself.
- Tap a car to get in.

## Tips

- Lose your wanted level by driving into the spray shop (costs cash).
- Weapons are sold at the gun shop.
- Settings has difficulty, day or night, and sound.

## How it's built

A single `index.html` file with no build step. Multiplayer uses Firebase Realtime Database, and the site is hosted on GitHub Pages.
