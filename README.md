# 坦克大战 (Tank Battle)

一个纯 HTML5 Canvas 实现的经典坦克大战（Battle City）网页小游戏，无需任何依赖，双击 `index.html` 即可游玩。

## ✨ 功能

- 🕹️ 键盘操控：方向键 / WASD 移动，空格 / J 射击
- 🧱 可破坏的砖墙、坚不可摧的钢墙、可跨越的水面
- 🦅 需要守护的基地（鹰）
- 🤖 敌方坦克 AI（随机移动 + 追踪射击）
- 🎯 得分、生命、关卡系统，共 3 关
- 🔊 基于 Web Audio 的简单音效
- 🎉 过关 / 通关 / 失败界面

## 🚀 运行方式

方式一：直接双击 `index.html` 用浏览器打开。

方式二（本地服务器）：

```bash
python -m http.server 8080
# 然后访问 http://localhost:8080
```

也可以直接部署到 GitHub Pages：仓库 → Settings → Pages → 选择 `main` 分支根目录。

## 🎮 操作说明

| 按键 | 功能 |
| ---- | ---- |
| `↑ ↓ ← →` 或 `W A S D` | 移动坦克 |
| `空格` / `J` | 开火 |
| `P` | 暂停 / 继续 |
| `Enter` | 开始 / 重新开始 |

## 📁 文件结构

```
tank-battle/
├── index.html   # 游戏全部代码（HTML + CSS + JS）
└── README.md
```

## 🧩 技术说明

- 使用 Canvas 2D 渲染，13×13 网格地图，每格 40px
- 纯原生 JavaScript，无第三方库
- 音效使用 Web Audio API 实时合成

Enjoy! 🎮
