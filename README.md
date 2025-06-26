# OxyUI

![Banner](https://i.postimg.cc/05LM1bYD/e0a4f47f-0736-4eee-9791-425172eba9ba.png)

**OxyUI** is a modern, lightweight Roblox Lua UI library designed for seamless integration and high performance. Optimized for Windows systems with a planned 2025 release, it offers customizable widgets, smooth animations, and developer-friendly features.

## 🔥 Features
- 🚀 **Fast Rendering**: Optimized for 60+ FPS
- 🎨 **Custom Themes**: Built-in dark/light modes + CSS-like styling
- 📱 **Responsive Design**: Adapts to all screen sizes
- 🛠 **Modular System**: Import only what you need
- 🔒 **Anti-Ban Protection**: Secure execution environment

## 📦 Installation
1. Download the latest release `.rbxm` file
2. Drag into Roblox Studio Explorer
3. Require the module:
```lua
local OxyUI = require(path.to.OxyUI)
```

## 💻 Usage Example
```lua
local ui = OxyUI.new()
local frame = ui:CreateFrame({
    Title = "Welcome",
    Size = {400, 250},
    Theme = "Dark"
})

frame:AddButton({
    Text = "Click Me",
    OnClick = function()
        print("Button pressed!")
    end
})
```

## 📜 Documentation
| Component      | Description                          |
|---------------|--------------------------------------|
| `UI.Create()` | Initializes new OxyUI instance       |
| `:AddButton()`| Creates interactive button element   |
| `:SetTheme()` | Changes color scheme (Dark/Light/Custom) |

## ⚙️ System Requirements
- Windows 10/11 (64-bit)
- Roblox Player (2025+ versions)
- Minimum 4GB RAM
- DirectX 11 compatible GPU

![GitHub](https://img.shields.io/badge/License-MIT-blue)
![Roblox](https://img.shields.io/badge/Roblox-2025%20Ready-red)

> 💡 **Pro Tip**: Use `ui:Optimize()` to boost performance in resource-intensive games