 # 🧱 suckless-dwm
 
![2](https://github.com/user-attachments/assets/0809d1dd-a868-41f5-9867-a2e062a99712)

> **Tiling made personal.**  
A minimal yet modern fork of the [suckless.org dwm](https://dwm.suckless.org/), crafted for daily comfort, modular builds, and an enhanced UX — all while preserving the original spirit.

---

## 🧩 About

This fork focuses on a balance of **minimalism**, **modularity**, and **daily usability**. It offers a clean build system and a well-organized configuration layout, making patching and upgrading easier than ever.

**Key Goals:**

- ✅ Preserve core suckless principles  
- 🗂 Modular versioned folders (e.g., `v6.4`)  
- 🎨 UX enhancements (gaps, status bar, systray)  
- 🔧 Clean integration of key patches  

---

## 🚀 Features

- Gaps between windows  
- Status bar transparency  
- Systray support  
- Xresources compatibility  
- Per-tag layout memory  
- Vanity gaps & flexible layout switching  
- Full modular build with versioning  

---

## 🛠️ Installation

### Dependencies

```bash
make
gcc
libX11
libXft
libXinerama
fontconfig
```

### Clone and Build

```bash
git clone https://github.com/rohanbatrain/suckless-dwm.git
cd suckless-dwm
sudo make clean install
```

### Optional: Local User Installation

```bash
make clean install PREFIX=$HOME/.local
```

---

## 🧪 Usage

To launch `dwm`, configure your `.xinitrc` or login manager with:

```bash
exec dwm
```

### Basic Keybindings

- `MOD + Enter` → Terminal  
- `MOD + d` → dmenu  
- `MOD + j / k` → Focus windows  
- `MOD + Shift + q` → Close window  
- `MOD + Shift + c` → Recompile dwm  

---

## 🧬 Customization

Customize your build by editing `config.h` and rebuilding:

- Appearance: borders, gaps, fonts, bar height  
- Behavior: layouts, keybindings, rules  
- Autostart apps, Xresources integration  

```bash
sudo make clean install
```

---

## 🧾 Version History

| Version | Description                                   | Date        |
|---------|-----------------------------------------------|-------------|
| v6.4    | Gaps, Xresources, Systray, Per-tag layout     | May 3, 2023 |

---

## 📜 License

Licensed under the **MIT License**, same as the original [suckless dwm](https://dwm.suckless.org/).

---

## 🤝 Credits

- [suckless.org](https://suckless.org) for the original dwm  
- The minimalist Linux community and patch authors  
 
 
