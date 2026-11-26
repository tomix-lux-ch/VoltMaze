# VoltMaze

A neon 3D maze chase for the browser. Clear every energy pellet in the sector while four drones hunt you through the maze. Grab a power core to overcharge and turn the hunt around.

VoltMaze is an original game inspired by two classics: the first-person maze shooting of the 1980s and the pellet-and-chaser arcade games of the same era. It runs on PC, Mac, iPhone, Android and tablets, and can be installed as an app that works offline.

**Play:** [tomix-lux-ch.github.io/VoltMaze](https://tomix-lux-ch.github.io/VoltMaze/)

---

## Features

- **Real-time 3D** with glow effects, soft shadows and a smooth chase camera, plus a first-person mode.
- **Map view:** play the whole maze from above, arcade style, with the 3D view in a corner window.
- **A new maze every game,** randomly generated, with stargates on the left and right that take you to the other side.
- **Six sector themes:** Amethyst Vault, Ember Forge, Glacier Deep, Toxic Grove, Neon Rose and Golden Ruins.
- **Four drones with their own tactics:**

  | Drone | Color | How it plays |
  |---|---|---|
  | Hunter | red | chases you |
  | Flanker | pink | cuts you off |
  | Drifter | orange | wanders until it sees you |
  | Warden | green | guards the power cores |

  Pick their look: glossy spheres, detailed 3D monsters or translucent phantoms.
- **Grey alien agents** (optional) with stun guns that freeze you in place.
- **1 to 4 players:** choose the number of players on the start screen. In multiplayer, the other robots are computer-controlled rivals for now. They race you for the pellets and shoot at you, maze-shooter style.
- **A boss every 4th sector:** the Overseer, an armored eye-engine that fires energy orbs and gets angrier as it takes damage.
- **Power-ups:** spread shot, rapid fire, shield, freeze and turbo.
- **Bonus crystals** worth more points in every sector.
- **Generated synthwave soundtrack** that speeds up when danger is close.
- **High-score table** (top 10 with initials), three difficulty levels and a demo mode on the title screen.

## How to play

- **Goal:** eat all pellets to clear the sector.
- **Shooting a drone** blasts it back to its pen, but it comes back out.
- **Power core:** grab one to **overcharge**. For a few seconds the drones turn blue and flee, and destroying them scores 200, 400, 800 and 1600 points.
- **Jumping:** jump over a drone to escape a dead end.
- **Alien agents** stun you instead of killing you, but a stunned robot is easy prey. Two hits beam an agent away.
- **Extra life** every 10,000 points.
- **Players:** pick 1 to 4 on the start screen (or press 1 to 4). With 2 or more, rival robots collect pellets too. A shot robot is stunned for a moment and loses up to 100 points to the shooter. An overcharged robot can ram the others. Drones hunt whichever robot is closest, and a rival they catch is out for a few seconds. The scoreboard at the top left shows who leads the match.

## Controls

### Keyboard and mouse

| Action | Keys |
|---|---|
| Move | W A S D, arrow keys, or the mouse wheel (forward / back) |
| Turn | Q / E, or the mouse (after clicking into the game) |
| Fire | Left click or Space |
| Jump | Shift, J or right click |
| Map / 3D view | Tab |
| Camera (chase / first person) | C |
| Opponent look | V |
| Stone / brick walls | T |
| Aliens on / off | G |
| Bloom glow | B |
| Mute all sound | M |
| Pause | P |

In the **Map view**, the keys move you in screen directions (up = north) and the robot turns to face the way it goes.

### Touch (phone and tablet)

| Action | How |
|---|---|
| Move | Left thumb: a joystick appears where you touch |
| Look / aim | Drag with the right thumb |
| Fire, jump | **FIRE** and **JUMP** buttons |
| Map / 3D view, camera, pause | **MAP**, **CAM** and **II** buttons |

Phones and tablets start in the Map view, which is easier to steer with a thumb. A **How to play** card opens on the first visit, and you can open it again from the title screen.

### Gamepad (Xbox style)

| Action | Button |
|---|---|
| Move | Left stick |
| Look (in the Map view: aim) | Right stick |
| Fire | RT, RB or X |
| Jump | A or LB |
| Camera | Y |
| Map / 3D view | Back |
| Pause | Start |

### Retro USB joystick (for example a Competition Pro)

| Action | Control |
|---|---|
| Move forward / back | Stick up / down |
| Turn (in the Map view: move) | Stick left / right |
| Fire | Buttons 1 and 3 |
| Jump | Buttons 2 and 4 |

The joystick's auto-fire switch works too.

## Settings

Open **SETTINGS** on the title or pause screen. Everything is remembered in the browser.

| Setting | Options |
|---|---|
| Difficulty | Easy (5 lives), Normal (3), Hard (2). Changes speed, overcharge time, stun time and boss health. |
| Camera | Chase or first person |
| View | 3D or map |
| Opponents | Spheres, 3D monsters or phantoms |
| Aliens | On / off |
| Players | 1 (solo) to 4. Also on the start screen. |
| Walls | Stone or brick |
| Music volume | 0 to 100 % |
| Sound FX | On / off |
| Bloom glow | On / off |
| Screen shake | On / off |
| Sector intro | On / off |

## Offline version

Want the game as a single file? Download **voltmaze-full.html** from the [Releases](https://github.com/tomix-lux-ch/VoltMaze/releases) page. It has everything inside and works without internet: double-click it on a PC, or copy it to a phone and open it in the browser.

## Install as an app

- **iPhone / iPad:** open the [game](https://tomix-lux-ch.github.io/VoltMaze/) in **Safari**, tap **Share**, then **Add to Home Screen**.
- **Android:** open the [game](https://tomix-lux-ch.github.io/VoltMaze/) in **Chrome**, then tap **⋮**, then **Install app** (or **Add to Home screen**).

After the first visit the game also runs offline. When a new version comes out, the app updates itself on the next visit with internet.

## About this repository

This repository holds the finished, installable web app (PWA) that GitHub Pages serves:

| File | What it is |
|---|---|
| `index.html` | The whole game: page, styles and code in one file |
| `manifest.webmanifest` | App name, icons and colors for installing |
| `sw.js` | Service worker for offline play |
| `icons/` | App icons |
| `preview.jpg` | Picture shown when the link is shared |

Built with plain JavaScript and [Three.js](https://threejs.org/), with no frameworks. All graphics and sounds are generated in code.

## Credits

- **Three.js** r128, © three.js authors, MIT License.
- **Orbitron** font by Matt McInerney, SIL Open Font License.
- Game design, code, models, music and icons: original work made for VoltMaze.
