# LuckPerms-Folia

![Java Version](https://img.shields.io/badge/Java-21-orange)
![Target](https://img.shields.io/badge/Target-Paper%20%2F%20Folia%20%2F%20Velocity-blue)

**LuckPerms-Folia** is a lightweight Folia-compatible fork of LuckPerms made for **BTC-CORE**, **Paper/Folia 1.21.11+**, and **Velocity 3.x**.

It removes old legacy support and focuses on better performance, async handling, and modern Paper/Folia APIs.

> [!WARNING]
> Some old LuckPerms addons/plugins may not work correctly because this fork is optimized for Folia and async environments.

---

# ✨ Features

- Native **Folia** support
- Optimized for **BTC-CORE**
- Async-safe permission handling
- MiniMessage support (`<gradient>`, `<rainbow>`, etc.)
- Async tab completion
- Modern Paper APIs
- Removed old Minecraft version support
- Faster database handling with **HikariCP**

---

# ⚙️ Config

## Main Settings

| Setting | Default | Description |
|---|---|---|
| `use-minimessage` | `true` | Enable MiniMessage formatting |
| `use-minimessage-for-metadata` | `true` | Use MiniMessage in prefixes/suffixes |
| `folia-context-enabled` | `true` | Enable Folia region contexts |

---

# 🛠 Build

Requires **Java 21**

```bash
git clone https://github.com/neonjava/luckperm-folia.git
cd LuckPerms-Paper-Folia-Velocity-1.21.11

./gradlew clean build -x test
```

## Built Files

### Paper/Folia
```txt
bukkit/loader/build/libs/LuckPerms-Bukkit-5.5.24.jar
```

### Velocity
```txt
velocity/build/libs/LuckPerms-Velocity-5.5.24.jar
```

---

# 🤝 Credits

Original project:
https://github.com/LuckPerms/LuckPerms

This is a Folia-compatible fork/port made for Paper/Folia and Velocity environments.

---

# 📜 License

MIT License. Original LuckPerms licenses still apply.