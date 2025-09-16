# 👋 Hey, I'm zvtix [April]

🎮 Roblox Developer | 💻 Scripter | 🕹️ Exploiting

Welcome to my GitHub profile! I’m passionate about building fun, interactive, and immersive experiences in **Roblox Studio** using **Lua scripting**.  
I also explore game mechanics, event systems, and performance optimization to bring ideas to life.  


## 🚀 Skills & Tools
- 🟢 **Roblox Studio** – Game building & environment design  
- 🟢 **Lua Scripting** – Gameplay mechanics, automation & systems  
- 🟢 **UI/UX in Roblox** – Player-friendly interfaces & menus  
- 🟢 **GitHub** – Version control & open-source collaboration  


## 📌 Featured Projects
- 🔨 **Custom Event System** – A Roblox event inspired by Adopt Me’s mechanics  
- ⚡ **Auto Swing Tool** – Scripted farming/automation systems  
- 🎨 **Game UI Framework** – Smooth and responsive in-game menus  


## Example: Module Usage (Safe snippet)
```lua
-- Example: requireable module pattern (safe, non-exploitative)
local Inventory = {}
Inventory.__index = Inventory

function Inventory.new()
  return setmetatable({items = {}}, Inventory)
end

function Inventory:addItem(itemId, qty)
  assert(type(itemId) == "string", "itemId must be string")
  qty = qty or 1
  self.items[itemId] = (self.items[itemId] or 0) + qty
end

function Inventory:getCount(itemId)
  return self.items[itemId] or 0
end

return Inventory


## 📫 Connect With Me
- 🌐 GitHub: [@qxt1on](https://github.com/qxt1on)  
- 💬 Discord: **qxt1on**  
