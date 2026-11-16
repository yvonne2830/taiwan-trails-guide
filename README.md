# 台灣山林步道與旅遊指南 (Taiwan Trails Guide)

這是一個遵循 **`AGENTS.md`** 規範開發的台灣經典步道與旅遊景點介紹網站，內容全部基於官方公開山林資訊原創整理，無任何版權疑慮。

## 專案特色
- **規則驅動擴充（Rule-Driven Development）**：透過根目錄的 `AGENTS.md` 明確規範設計系統、HTML 模板（`templates/trail-template.html`）、檔案命名與首頁同步機制，讓 AI 能快速新增各地步道頁面。
- **結構化路線資訊**：每條步道皆配備「4 格核心數據卡（里程、時間、海拔、難度）」、分段路線攻略、交通接駁與裝備清單。
- **地區動態篩選**：首頁支援依北部、中部、南部、東部地區即時篩選步道卡片。

## 如何上傳至 GitHub 並開啟 GitHub Pages
1. 在 GitHub 建立一個新的 **Public Repository**（例如 `taiwan-trails-guide`，`Add README` 保持 OFF）。
2. 將本資料夾內的全部 6 個項目（`AGENTS.md`、`README.md`、`index.html`、`assets/`、`trails/`、`templates/`）拖曳上傳並 Commit。
3. 進入 Repository 的 **Settings → Pages**，在 **Branch** 選擇 `main` 與 `/ (root)`，點擊 **Save**。
4. 等待約 1～2 分鐘重新整理，即可取得公開網址（`https://你的帳號.github.io/taiwan-trails-guide/`）。
