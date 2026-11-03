# SHADOW BLADE ⚔️

A high-performance, polished, 2D silhouette fighting game inspired by **Shadow Fight**, crafted entirely in vanilla JavaScript and HTML5 Canvas with procedural Web Audio sound synthesis.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Technology](https://img.shields.io/badge/HTML5-Canvas%202D-orange.svg)
![Audio](https://img.shields.io/badge/Audio-Web%20Audio%20API-green.svg)
![Dependencies](https://img.shields.io/badge/dependencies-0%20(Pure%20Vanilla)-success.svg)

---

## 🌟 Key Features

- **Articulated Silhouette Rigging**: 2D skeletal forward kinematics render dark humanoid silhouettes with depth layering (darker back limbs, front obsidian limbs), glowing demonic eye visors, and Verlet-physics headband tails blowing in the wind.
- **Glowing Katana & Weapon Trails**: Real-time quad-strip blade trails rendered with additive blend modes (`lighter`) that bloom into arcs during combos.
- **Antigravity Momentum & Physics**: Custom aerial hang-time near jump apex, wall-kick rebounds, dashing invincibility frames (i-frames), and knockdown recovery rolls.
- **Directional Combat & Combo Engine**:
  - Triple Blade Slash (`J` → `J` → `J`)
  - Lunging Viper Thrust (`Forward` + `J`)
  - Rising Crescent Launcher (`Up` + `J`)
  - Meteor Air Dive (`Air` + `J`)
  - Low Sweep Knockdown (`Down` + `K`)
  - Void Execution Shadow Ultimate (`Space` / `U` at 100% Ki)
- **Procedural Audio Synthesizer**: Zero external audio files required! Synthesizes blade slashes, heavy impacts, metallic sword parries, and a real-time generative 112 BPM taiko/synth background beat.
- **Multiple Game Modes**:
  - ⚡ **Versus AI Duel**: Adaptive sparring AI with spacing, jump attacks, and counter-attacks.
  - ⚔️ **2-Player Local**: Side-by-side local PvP combat on a single keyboard.
  - 🥋 **Training Dojo**: Infinite regenerative practice dummy.
- **Mobile Responsive**: Virtual touch wireframe controls automatically adapt for mobile and tablet touchscreens.

---

## 🎮 Controls

### Player 1 (Default)
| Action | Key | Description |
| :--- | :---: | :--- |
| **Move / Advance** | <kbd>A</kbd> / <kbd>D</kbd> | Move left and right |
| **Float Jump** | <kbd>W</kbd> | Acrobatic high jump with apex float |
| **Crouch** | <kbd>S</kbd> | Duck below high attacks |
| **Strike / Slash** | <kbd>J</kbd> | Chain 3 times for full blade combo |
| **Kick** | <kbd>K</kbd> | Snap kick (or <kbd>S</kbd>+<kbd>K</kbd> for sweep) |
| **Shadow Dash** | <kbd>L</kbd> | Fast dodge roll with i-frames |
| **Shadow Art** | <kbd>Space</kbd> / <kbd>U</kbd> | Unleash ultimate when Ki bar is full |
| **Guard / Parry** | Hold <kbd>Back</kbd> | Mitigate 85% damage with metallic sparks |
| **Command Manual** | <kbd>C</kbd> / <kbd>H</kbd> | Toggle on-screen controls modal |

### Mobile & Tablet Touch Controls
- **Left Thumb (D-Pad)**:
  - <kbd>▲</kbd> Jump / Wall Rebound
  - <kbd>◀</kbd> Move Left / Guard
  - <kbd>▶</kbd> Move Right / Advance
  - <kbd>▼</kbd> Crouch / Low Sweep
- **Right Thumb (Action Cluster)**:
  - <kbd>J</kbd> Primary Strike (Tap for 3-hit combo)
  - <kbd>K</kbd> Kick Attack
  - <kbd>DASH</kbd> Shadow Dash / Roll
  - <kbd>KI</kbd> Void Execution (Shadow Art)
- **Top Quick Bar**:
  - <kbd>📱</kbd> Manual Touch Controls Toggle
  - <kbd>⛶</kbd> Fullscreen Mode

### Player 2 (Local PvP)
- **Move / Jump / Crouch**: <kbd>Arrow Keys</kbd>
- **Strike**: <kbd>1</kbd> or <kbd>Numpad 1</kbd>
- **Kick**: <kbd>2</kbd> or <kbd>Numpad 2</kbd>
- **Dash**: <kbd>3</kbd> or <kbd>Numpad 3</kbd>
- **Shadow Ultimate**: <kbd>4</kbd> or <kbd>Numpad 4</kbd>

---

## 🚀 How to Play

### Option 1: Double-Click
Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server
```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```
Visit `http://localhost:8080` in your browser.

---

## 🌐 Deploy to GitHub Pages (Free Instant Play Link)

1. Push this repository to GitHub.
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Your game will be live at `https://<your-username>.github.io/<repo-name>/`!

---

## 📜 License
MIT License. Feel free to modify, expand, and share!

