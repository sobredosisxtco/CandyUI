# 🍬 CandyUI

**The sweetest and simplest UI library for Roblox.**

Designed so you can create beautiful interfaces **with the least effort possible**.

## ✨ Philosophy

- **Extremely easy to use**
- Only pass what you need (`Name`, `Callback`, `Desc`, etc.)
- No complicated setups
- Perfect for scripters who want something nice quickly

## 📥 Installation

```lua
local CandyUI = loadstring(game:HttpGet("https://github.com/sobredosisxtco/CandyUI/raw/refs/heads/main/src"))()
```
## 🚀 Basic Example

```lua
local Window = CandyUI:CreateWindow({
    Title = "My CandyUI"
})

local Tab = Window:CreateTab({
    Name = "Home"
})

Tab:AddLabel({
    Text = "Welcome to CandyUI! 🍬"
})

Tab:AddButton({
    Name = "Click me",
    Desc = "This button has a description",
    Callback = function()
        print("Button pressed!")
    end
})
```

Made with ❤️ by @sobredosisxtco
