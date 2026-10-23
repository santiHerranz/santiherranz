<!--
  Retro-arcade profile. Pixel text, headers and buttons are SVGs in assets/ (built from a 5x7 bitmap font,
  so they render without web fonts). GitHub strips `style` and `object-fit` from README HTML, so every
  screenshot is pre-cropped: 640x360 (16:9) for LEVEL SELECT, 320x320 for HALL OF FAME.
-->

<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Santi Herranz — web game developer, Barcelona. An arcade screen with a blue and a red castle, troops marching along a front line between them, and meteors falling.">
</p>

<h3 align="center"><img src="assets/h-player-1.svg" height="44" alt="Player 1"></h3>

<p align="center">
  I make games that run in a browser tab — from <b>13 KB jam entries</b> to an <b>online RTS with its own game server</b>.<br>
  TypeScript on the client, Node or .NET on the server, and a soft spot for armies, rockets and pixel art.
</p>

```text
PLAYER 1 ........ Santi Herranz
CLASS ........... Web game developer
BASE ............ Barcelona
SPECIAL MOVE .... Real-time multiplayer, server-authoritative
ACHIEVEMENTS .... js13kGames entrant 2021 · 2022 · 2023 · 2024
STATUS .......... Open to work & collabs  ▶  see INSERT COIN
```

<h3 align="center"><img src="assets/h-now-playing.svg" height="44" alt="Now playing"></h3>

<p align="center">
  <a href="https://santiherranz.itch.io/tiny-swords-wars"><img src="assets/tiny-swords-wars.gif" width="640" alt="Tiny Swords Wars gameplay: the blue army storms the red castle"></a>
</p>

<p align="center">
  <b>TINY SWORDS WARS</b> — a free 1v1 medieval RTS in your browser.<br>
  You don't click every soldier: you draw the front, conquer the provinces and raze the rival castle.
</p>

<p align="center">
  <a href="https://santiherranz.itch.io/tiny-swords-wars"><img src="assets/btn-play-itch.svg" height="40" alt="Play Tiny Swords Wars free on itch.io"></a>
</p>

<p align="center">
  <sub>Early access · Ranked Season 1 from 1 Nov 2026 · Colyseus + PixiJS · Art: <a href="https://pixelfrog-assets.itch.io/tiny-swords">Tiny Swords</a> by Pixel Frog</sub>
</p>

<h3 align="center"><img src="assets/h-multiplayer.svg" height="44" alt="Multiplayer mode"></h3>

<table>
<tr>
<td width="46%" valign="top">
<a href="https://santiherranz.itch.io/tiny-swords-wars"><img src="assets/tiny-swords-wars-map.png" width="100%" alt="Tiny Swords Wars map: provinces, fog of war and a yellow belt line leading troops to the front"></a>
</td>
<td valign="top">
<b>Under the hood of Tiny Swords Wars</b>
<ul>
<li><b>Server-authoritative netcode</b> on Colyseus: quick match, private 4-digit rooms, rematch and a 20 s reconnect window.</li>
<li><b>Real fog of war</b>: the server only sends what your side can see. No map hacks.</li>
<li><b>Bots that play fair</b>: Easy, Normal and Hard, with your rules and your vision, waiting in the lobby 24/7.</li>
<li><b>Procedural kingdoms</b>: a new map every match, with provinces, rivers, forests and gold mines.</li>
<li><b>Ranked seasons</b>: everyone starts each season's table at 1000 points.</li>
</ul>
<sub>Before it came a reusable Colyseus + Canvas room template and online Battleship and Connect Four prototypes.</sub>
</td>
</tr>
</table>

<h3 align="center"><img src="assets/h-level-select.svg" height="44" alt="Level select"></h3>

<table>
<tr>
<td width="50%" valign="top">
<a href="https://santiherranz.itch.io/rockets-and-drones-firefighter"><img src="assets/firefighter.jpg" width="100%" alt="Rockets and Drones: Firefighter — a 3D forest with drone launch pads"></a>
<br><b>ROCKETS &amp; DRONES: FIREFIGHTER</b>
<br>Fight wildfires with tech from the future.
<br><sub>2026 · Three.js</sub>
<br><a href="https://santiherranz.itch.io/rockets-and-drones-firefighter"><img src="assets/btn-play.svg" height="30" alt="Play Rockets and Drones: Firefighter"></a>
</td>
<td width="50%" valign="top">
<a href="https://santiherranz.itch.io/online-battleship"><img src="assets/battleship.png" width="100%" alt="Classic Battleship — fleet and enemy grids mid-game"></a>
<br><b>CLASSIC BATTLESHIP WITH AI ASSIST</b>
<br>The naval duel vs the CPU, with an optional AI hint and a leaderboard.
<br><sub>2026 · Canvas · Supabase</sub>
<br><a href="https://santiherranz.itch.io/online-battleship"><img src="assets/btn-play.svg" height="30" alt="Play Classic Battleship"></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://santiherranz.itch.io/rockfall-command"><img src="assets/rockfall.jpg" width="100%" alt="Rockfall Command key art: meteors raining over a city"></a>
<br><b>ROCKFALL COMMAND</b>
<br>My take on Atari's 1980 Missile Command: defend Earth from the meteor storm.
<br><sub>2025–2026 · Canvas · Supabase</sub>
<br><a href="https://santiherranz.itch.io/rockfall-command"><img src="assets/btn-play.svg" height="30" alt="Play Rockfall Command"></a>
</td>
<td width="50%" valign="top">
<a href="https://santiherranz.github.io/SumoFighters/"><img src="assets/sumofighters.png" width="100%" alt="SumoFighters — two robots in a sumo ring, score 3 vs 1"></a>
<br><b>SUMOFIGHTERS</b>
<br>A robot sumo simulator for testing fight strategies.
<br><sub>2021 · JavaScript</sub>
<br><a href="https://santiherranz.github.io/SumoFighters/"><img src="assets/btn-play.svg" height="30" alt="Play SumoFighters"></a>
<a href="https://github.com/santiHerranz/SumoFighters"><img src="assets/btn-code.svg" height="30" alt="SumoFighters source code"></a>
</td>
</tr>
</table>

<h3 align="center"><img src="assets/h-hall-of-fame.svg" height="44" alt="Hall of fame"></h3>

<p align="center">
  <a href="https://js13kgames.com/">js13kGames</a>: every year, a whole game in <b>13 kilobytes</b> zipped, built around a theme announced on day one.
</p>

<table>
<tr>
<td width="25%" valign="top" align="center">
<a href="https://js13kgames.com/games/rocket-cargo"><img src="assets/js13k-2021-rocket-cargo.png" width="100%" alt="Rocket Cargo — a rocket on a launch pad"></a>
<br><b>ROCKET CARGO</b>
<br><sub>2021 · theme: Space</sub>
<br><a href="https://js13kgames.com/games/rocket-cargo">Play</a> · <a href="https://github.com/santiHerranz/RocketCargo">Code</a>
</td>
<td width="25%" valign="top" align="center">
<a href="https://js13kgames.com/games/escape-from-death-hole"><img src="assets/js13k-2022-death-hole.png" width="100%" alt="Escape from Death Hole cover art"></a>
<br><b>ESCAPE FROM DEATH HOLE</b>
<br><sub>2022 · theme: Death</sub>
<br><a href="https://js13kgames.com/games/escape-from-death-hole">Play</a> · <a href="https://github.com/santiHerranz/js13k2022-Death">Code</a>
</td>
<td width="25%" valign="top" align="center">
<a href="https://js13kgames.com/games/battle-commander-middle-ages"><img src="assets/js13k-2023-battle-commander.png" width="100%" alt="Battle Commander: two medieval armies clash"></a>
<br><b>BATTLE COMMANDER</b>
<br><sub>2023 · theme: 13th Century</sub>
<br><a href="https://js13kgames.com/games/battle-commander-middle-ages">Play</a> · <a href="https://github.com/santiHerranz/js13k2023-Battle-commander-Middle-ages">Code</a>
</td>
<td width="25%" valign="top" align="center">
<a href="https://js13kgames.com/games/no-flight-zone-13"><img src="assets/js13k-2024-no-flight-zone-13.png" width="100%" alt="No Flight Zone 13 cover: a biplane firing"></a>
<br><b>NO FLIGHT ZONE 13</b>
<br><sub>2024 · theme: Triskaidekaphobia</sub>
<br><a href="https://js13kgames.com/games/no-flight-zone-13">Play</a> · <a href="https://github.com/santiHerranz/js13k-2024">Code</a>
</td>
</tr>
</table>

<h3 align="center"><img src="assets/h-inventory.svg" height="44" alt="Inventory"></h3>

<table align="center">
<tr>
<td><b>Game</b></td>
<td>
<img src="https://img.shields.io/badge/TypeScript-0b1026?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript">
<img src="https://img.shields.io/badge/Canvas_2D-0b1026?style=for-the-badge&logo=html5&logoColor=E34F26" alt="Canvas 2D">
<img src="https://img.shields.io/badge/PixiJS-0b1026?style=for-the-badge" alt="PixiJS">
<img src="https://img.shields.io/badge/Three.js-0b1026?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js">
<img src="https://img.shields.io/badge/LittleJS-0b1026?style=for-the-badge" alt="LittleJS">
<img src="https://img.shields.io/badge/Vite-0b1026?style=for-the-badge&logo=vite&logoColor=A78BFA" alt="Vite">
</td>
</tr>
<tr>
<td><b>Netcode</b></td>
<td>
<img src="https://img.shields.io/badge/Colyseus-0b1026?style=for-the-badge" alt="Colyseus">
<img src="https://img.shields.io/badge/WebSockets-0b1026?style=for-the-badge" alt="WebSockets">
<img src="https://img.shields.io/badge/Node.js-0b1026?style=for-the-badge" alt="Node.js">
</td>
</tr>
<tr>
<td><b>Backend</b></td>
<td>
<img src="https://img.shields.io/badge/C%23_%2F_.NET-0b1026?style=for-the-badge&logo=dotnet&logoColor=A179DC" alt="C# / .NET">
<img src="https://img.shields.io/badge/Express-0b1026?style=for-the-badge&logo=express&logoColor=white" alt="Express">
<img src="https://img.shields.io/badge/Supabase-0b1026?style=for-the-badge&logo=supabase&logoColor=3ECF8E" alt="Supabase">
</td>
</tr>
<tr>
<td><b>Ship it</b></td>
<td>
<img src="https://img.shields.io/badge/Railway-0b1026?style=for-the-badge&logo=railway&logoColor=white" alt="Railway">
<img src="https://img.shields.io/badge/Azure-0b1026?style=for-the-badge" alt="Azure">
<img src="https://img.shields.io/badge/GitHub_Pages-0b1026?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages">
<img src="https://img.shields.io/badge/itch.io-0b1026?style=for-the-badge&logo=itchdotio&logoColor=FA5C5C" alt="itch.io">
</td>
</tr>
<tr>
<td><b>Tests</b></td>
<td>
<img src="https://img.shields.io/badge/Vitest-0b1026?style=for-the-badge&logo=vitest&logoColor=FCC72B" alt="Vitest">
<img src="https://img.shields.io/badge/Playwright-0b1026?style=for-the-badge" alt="Playwright">
</td>
</tr>
<tr>
<td><b>13 KB tricks</b></td>
<td>
<img src="https://img.shields.io/badge/Roadroller-0b1026?style=for-the-badge" alt="Roadroller">
<img src="https://img.shields.io/badge/Closure_Compiler-0b1026?style=for-the-badge" alt="Closure Compiler">
</td>
</tr>
</table>

<h3 align="center"><img src="assets/h-insert-coin.svg" height="44" alt="Insert coin"></h3>

<p align="center">
  <b>Open to work</b>: freelance, contracts and game-jam teams.<br>
  Especially real-time multiplayer and anything that has to run in a browser tab.
</p>

<p align="center">
  <a href="https://santiherranz.itch.io/"><img src="assets/btn-itch.svg" height="36" alt="Santi Herranz on itch.io"></a>
  <a href="https://x.com/santiherranz"><img src="assets/btn-x.svg" height="36" alt="@santiherranz on X"></a>
</p>

<p align="center">
  <img src="assets/footer.svg" width="420" alt="Thanks for playing. Continue?">
</p>
