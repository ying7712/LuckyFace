🧧 LuckyFace 幸運笑臉抽籤機

以 ESP32 微控制器結合 OLED 顯示器、按鈕與三色 LED，打造一款互動式抽籤機

---

🎯 功能特色

- 🖼 16x16 中文點陣籤詩顯示
- 😎 三種笑臉表情隨機動畫倒數
- 🟢🟡🔴 LED 顯示籤運
- 🎲 加權抽籤機制（支援大吉～凶）

---

🛠 使用元件

- ESP32 Dev Board
- SSD1306 OLED 顯示器（I2C）
- 按鈕 x 1
- 三色 LED（紅黃綠）
- MicroPython

---

🚀 使用方法

1. 將 `main.py` 上傳至 ESP32（使用 Thonny）
2. 接好以下硬體腳位：
   - OLED: SDA → GPIO21, SCL → GPIO22
   - 按鈕：GPIO36（預設上拉）
   - LED：紅→GPIO16, 黃→GPIO12, 綠→GPIO13
3. 通電開機！按下按鈕就能開始抽籤啦！

---

👩‍💻 作者

陳彥吟

技術支援夥伴：ChatGPT😎

---

