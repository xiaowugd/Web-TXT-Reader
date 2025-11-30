# Web-TxT-Reader
# 极简 Web 本地小说阅读器

<p align="center">
  <img src="https://img.shields.io/badge/build-HTML5-orange" alt="HTML5">
  <img src="https://img.shields.io/badge/storage-IndexedDB-blue" alt="IndexedDB">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/size-<50KB-lightgrey" alt="Size">
</p>

## 📖 Introduction (简介)

**Web-TxT-Reader** is a lightweight, single-file HTML5 novel reader designed for local TXT files. It operates entirely in your browser without any backend server, ensuring **100% privacy** and data security. 

Powered by **IndexedDB**, it persistently stores your library and reading progress locally. With its **clean and immersive UI**, smart chapter parsing, and highly customizable settings, Web-TxT-Reader offers a smooth, native app-like experience directly in your browser.

**Web-TxT-Reader** 是一款基于 HTML5 开发的极简**单文件**本地 TXT 小说阅读器。它零依赖、无后端，所有数据通过 **IndexedDB** 存储在您的浏览器本地，不仅加载速度极快，更确保了**绝对的隐私安全**。

它拥有**现代简洁的沉浸式 UI**，内置正则智能分章算法，支持进度自动保存、数据备份与恢复，是极客与小说爱好者的阅读利器。

---

## ✨ Key Features (核心特点)

* **🚀 Zero Dependencies (零依赖)**: The entire app is contained in a single HTML file. No installation, no Node.js, no Python. Just double-click to run.
    * 单文件架构，无需安装，双击 HTML 即可运行。
* **🔒 Privacy First (隐私优先)**: No data is uploaded to any server. Everything lives in your browser's local storage.
    * 无后端设计，所有书籍和进度仅保存在本地浏览器中，安全无忧。
* **🧠 Smart Parsing (智能分章)**: Automatically detects chapters using advanced Regex (supports `Chapter`, `第x章`, `Volume`, `Introduction`, etc.) and generates a Table of Contents.
    * 内置智能正则解析，自动识别各类章节标题并生成目录。
* **💾 Persistent Storage (持久化存储)**: Uses IndexedDB to save books and reading progress. You can close the browser and resume exactly where you left off.
    * 利用 IndexedDB 技术实现大容量存储，刷新或关闭浏览器不丢失进度。

---

## 🛠 Functionality (功能列表)

### 📚 Library Management (书架管理)
* **Multi-Encoding Support**: Smart import for UTF-8, GBK (common for Chinese novels), and Big5.
    * 支持多种编码导入，解决中文乱码问题。
* **Progress Tracking**: Visual percentage indicators on book covers.
    * 封面实时显示阅读进度百分比。
* **Data Backup**: Export your entire library and reading progress to a JSON file and restore it anytime.
    * 支持一键导出/导入备份，数据永不丢失。

### 📖 Reading Experience (阅读体验)
* **Customizable Fonts**: Switch between Sans-serif (黑体), Serif (宋体), and Kaiti (楷体).
    * 提供黑体、宋体、楷体三种字体切换。
* **Theme Engine**: 4 built-in themes: Light (Day), Warm (Eye-protection), Green, and Dark (Night mode).
    * 内置日间、护眼（暖色/绿色）及夜间模式。
* **Layout Control**: Adjustable font size and content width (max-width).
    * 支持自由调节字号大小及阅读版心宽度。
* **Smooth Navigation**: Click areas to turn pages, or use "Previous/Next Chapter" buttons. Auto-scrolls to last position.

### 🔍 Utility (实用工具)
* **Full-Text Search**: Search for keywords within the current book with context snippets.
    * 支持全文关键词搜索，并显示上下文摘要。
* **Table of Contents**: Sidebar navigation for quick chapter jumping.
    * 侧边栏目录跳转。
* **Responsive Design**: Perfectly optimized for both Desktop and Mobile.
    * 完美适配桌面端与移动端。

---

## 🚀 Usage (如何使用)

1.  **Download**: Get the `Web-TxT-Reader.html` file from the [Releases](../../releases) page.
2.  **Open**: Double-click the file to open it in any modern browser (Chrome, Edge, Safari, Firefox).
3.  **Import**: Click the **`+`** button on the top right to select your local `.txt` files.
    * *Tip: Select "GBK" encoding if you see garbled text (common for older Chinese txt files).*
4.  **Enjoy**: Start reading! Your progress is saved automatically.

---

## 🤝 Contributing (贡献)

Issues and Pull Requests are welcome! 

欢迎提交 Issue 和 PR！

## 📄 License

This project is licensed under the [MIT License](LICENSE).
