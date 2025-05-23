# IMG-Download-Extensions  
## 圖片嗅探下載器

**IMG-Download-Extensions** 是一款開源的 Chrome、Firefox、Edge 擴充元件，能夠自動嗅探當前網頁上的所有圖片，並提供使用者快速預覽與下載的功能，讓圖片利用更加高效便利。

![IMG-Download-Extensions cover](https://github.com/zz22558822/IMG-Download-Extensions/blob/main/images/IMG-Download-Extensions.png)  

---

<p align="center">
  <a href="https://chromewebstore.google.com/detail/bfkmokppkophngpacodnjkpngpabkdco">
    <img src="https://github.com/Chek-Old/image/blob/main/Browser/Chrome.png?raw=true" alt="前往 Chrome 獲取擴充元件" width="30%" style="margin: 0 10px;">
  </a>
  <a href="https://addons.mozilla.org/zh-TW/firefox/addon/img-download-extensions/">
    <img src="https://github.com/Chek-Old/image/blob/main/Browser/Firefox.png?raw=true" alt="前往 Firefox 獲取擴充元件" width="30%" style="margin: 0 10px;">
  </a>
  <a href="https://chromewebstore.google.com/detail/bfkmokppkophngpacodnjkpngpabkdco">
    <img src="https://github.com/Chek-Old/image/blob/main/Browser/Edge.png?raw=true" alt="前往 Chrome 商店獲取擴充元件" width="30%" style="margin: 0 10px;">
  </a>
</p>

---


## 🔧 功能特色

- 🔍 自動嗅探目前網頁中所有圖片
- 🖼️ 提供圖片預覽介面
- 📥 快速下載單個圖片（選用）
- 🎨 支援黑暗模式切換
- 📦 支援圖片轉存為 PNG 格式（選用）

---


## 🔐 所需權限

| 權限       | 說明 |
|------------|------|
| **activeTab** | 暫時存取使用中的分頁，用於圖片嗅探 |
| **downloads** | 允許圖片轉為下載格式 |
| **scripting** | 注入腳本以動態渲染圖片預覽 |
| **tabs** | 存取目前分頁，用於篩選圖片資源 |

---


## 📝 更新紀錄

### 📌2025/4/14 — [v1.0.3](https://github.com/zz22558822/IMG-Download-Extensions/releases/tag/v1.0.3)
- ✅ 預覽圖新增圖片資訊框

### 📌2025/4/10 — [v1.0.2](https://github.com/zz22558822/IMG-Download-Extensions/releases/tag/v1.0.2)
- ✅ 更新 Firefox 支援
- ✅ 更新 Edge 支援
- 🔧 優化動態判斷 WebExtension API

### 📌2025/4/9 — [v1.0.1](https://github.com/zz22558822/IMG-Download-Extensions/releases/tag/v1.0.1)
- ✅ 新增「轉存為 PNG」按鈕（預設關閉）
- 🔧 更新介面按鈕圖示
- 🧩 新增轉存為 PNG 的相關功能
- 💄 優化整體 UI 顯示與互動體驗

---


## 🔭 未來更新方向
- ✂️ DOM 元素選取與遮罩功能，方便標記與截圖
- 📥 一鍵下載所選圖片
- 🔘 按鈕製作展開式選單
- 🖼️ 預覽圖大小調整
- 💬 SweetAlert2 取代 console.error
- 🔗 網頁連結切換表格顯示

---


## 📂 原始碼與貢獻

本專案為開源項目，歡迎任何形式的貢獻（功能建議、Bug 回報、Pull Request）！  
👉 [前往 GitHub 儲存庫](https://github.com/zz22558822/IMG-Download-Extensions)

