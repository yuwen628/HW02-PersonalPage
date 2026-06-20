
Demo Website: https://yuwen628.github.io/HW02-PersonalPage/

# AI 人工智慧與程式開發作品集 — 科技藝術特展 🎨

這是一個專為展示 **AI 機器學習、創意編程（Creative Coding）與演算法藝術** 所設計的極簡主義個人形象網站。

本專案跳脫傳統資訊工程作品集的冰冷框架，以「**數理美學為核心，視覺藝術為載體**」，將程式碼、演算法與物理方程式轉化為 **9 個充滿張力的動態視覺藝術模組**。整站採用白底極簡風（Minimalist White），利用大氣的留白、精細的微交互，展現開發者兼具邏輯工程與數位美學的跨界硬實力。

---

## 🎨 核心設計美學

- **極簡主義白底風格**：精確控制對比度（純白背景與 zinc-800 深灰文字），搭配極具人文藝術感的西文襯線體 *Playfair Display* 與現代無襯線中文字體 *Noto Sans TC*，營造美術館特展般的專業質感。
- **無圖檔純代碼渲染**：九宮格所有視覺縮圖均使用 **原生 SVG 向量程式碼** 繪製而成，不依賴任何外部圖檔，保證極致的載入效能、無視網膜螢幕失真問題、且絕對不會發生死圖風險。
- **微細節科技動態**：微弱的科技點狀背景網格、流暢的卡片浮起懸停特效、以及隨著背景慢速漂移、脈動的抽象幾何，讓靜態網頁充滿生命力。

---

## 🧩 網站單元架構

本網站為單一 HTML 檔案（Single-File）架構，程式結構乾淨且便於託管。全站僅保留最純粹的三大核心單元：

| 單元 | 說明 |
|---|---|
| **首頁 (Hero Section)** | 大氣的特展級主標題、副標題，與指引點擊的互動按鈕。 |
| **科技藝術九宮格 (Tech-Art 9-Grid)** | 本專案的核心靈魂，內含 9 個精美的科技藝術展示卡。點擊卡片將啟動內建的彈窗系統（Modal System），展示細緻的專案細節：科技藝術核心概念與數學原理說明、採用的核心技術棧（Tech Stack）與渲染量化指標、動態渲染的生成藝術核心代碼預覽 (Creative Code Snippets)。 |
| **關於我 (About Me)** | 精準描述學員的定位與追求，傳達「程式碼為墨，數學公式為筆」的創作核心價值。 |

---

## 🌌 九宮格演算法專案一覽

在九宮格中，我們將複雜的底層技術轉化為具有高度感官衝擊的科技藝術成果：

| # | 專案名稱 | 核心美學 / 數學原理 | 核心技術棧 |
|---|---|---|---|
| 01 | 奇異吸引子混沌軌跡 | Clifford 吸引子非線性遞迴方程、百萬粒子點雲、對數尺度色彩映射 | Python, NumPy, Canvas API, GLSL |
| 02 | AI神經風格特徵融合 | VGG-19 卷積神經網絡、Gram 矩陣特徵提取與風格融合 | PyTorch, Style Loss, TensorFlow Lite |
| 03 | 黃金比例與生長分形 | Julia & Mandelbrot 複數迭代、斐波那契螺旋、極坐標系調變 | p5.js, WebGL, HTML5 Canvas |
| 04 | 量子流體非線性粒子 | Navier-Stokes 流體力學偏微分方程、Perlin Noise 與 3D 向量場 | GPU Shaders, Perlin Noise 3D |
| 05 | 數據山脊三維頻譜 | 聲學與光學頻譜快速傅立葉變換（FFT）、三維頂點高度動態映射 | Three.js, Web Audio API, FFT |
| 06 | 神經網絡拓撲曼陀羅 | 力導向圖（Force-Directed）排版演算法、彈簧力與斥力對稱平衡 | D3.js Force Simulation, SVG Projection |
| 07 | 虛擬鏡界高維度投影 | 四維超立方體（Tesseract）正交與透視投影、高維歐拉角旋轉 | Three.js Matrix4, Isometric Geometry |
| 08 | 資訊熵溢訊號故障偏移 | Bitwise Shift 位元截斷、RGB Split 色差偏移、像素混合模式 | Raw Byte Manipulation, Canvas API |
| 09 | 光波衍射全息光譜 | 惠更斯-菲涅耳原理偏振波干涉、數字孔徑複數相位衍射渲染 | GLSL Fragment Shader, WebGL Context |

---

## 🛠️ 開發技術棧與亮點

- **前端框架**：不依賴 React/Vue 等重型框架，使用輕量、高性能的 **純原生 JavaScript (Vanilla JS)** 驅動所有 DOM 交互。
- **樣式切版**：採用最新 Tailwind CSS CDN 載入，全面使用語意化 Utility Classes 進行敏捷開發。
- **字型服務**：導入 Google Fonts（Inter, Noto Sans TC, Fira Code, Playfair Display）。
- **互動體驗**：
  - **行動版響應式設計 (RWD)**：支援手機與平板，配備全手寫無框架的 Hamburger 側邊選單動畫。
  - **自訂 Toast 通知元件**：棄用傳統瀏覽器內建 `alert()`，改寫自訂平滑彈出式 Toast 通知，帶給觀看者無縫優雅的提示體驗。
  - **背景滾動鎖定**：開啟作品詳情彈窗時，自動鎖定背景滾動，關閉後還原。

---

## 🚀 如何運行

本網站採用無編譯流程的純粹 HTML/JS 架構，完全不需要安裝任何額外的運行環境或 Node.js 套件：

1. **下載專案**：
   ```bash
   git clone https://github.com/yuwen628/HW02-PersonalPage.git
   cd HW02-PersonalPage
   ```

2. **運行網站**：
   - **方式 A（直接開啟）**：在檔案總管中，直接雙擊 `index.html` 即可使用您電腦上的預設瀏覽器開啟！
   - **方式 B（本地伺服器 — 推薦）**：如果您想讓資源加載與字體渲染更加標準，可以使用 VS Code 的 Live Server 套件，或者在終端機運行：
     ```bash
     python -m http.server 8000
     ```
     接著在瀏覽器輸入 `http://localhost:8000` 即可造訪。

---

## 📄 專案結構

```
HW02-PersonalPage/
├── index.html   # 網站主體（HTML + CSS + JavaScript 全部整合在單一檔案）
└── README.md    # 本說明文件
```

---

© 2026 AI 與程式開發應用班作品集. All rights reserved.
