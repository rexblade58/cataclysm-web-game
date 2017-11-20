# Cataclysm Web Game

Browser-based post-apocalyptic survival game built with vanilla JavaScript and HTML5 Canvas.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Gameplay

- Explore a procedurally generated wasteland
- Collect resources: wood, stone, food, water
- Avoid hostile enemies that chase you
- Survive as many days as possible
- Day/night cycle affects resource depletion

## Quick Start

`ash
git clone https://github.com/rexblade58/cataclysm-web-game.git
cd cataclysm-web-game
npx http-server public -p 8080
`

Open http://localhost:8080

## Controls

- WASD / Arrow Keys: Move player
- Survive by collecting resources before hunger depletes

## Structure

`
public/
  index.html     game entry point with HUD overlay
  src/
    game.js      core game loop, rendering, collision
package.json
`

## Planned Features

- Crafting system
- Base building
- Multiplayer co-op
- Sound effects and music

## Contributing

Pull requests welcome for any planned features or improvements.

## License

MIT © [Menard Rosal](https://github.com/rexblade58)

