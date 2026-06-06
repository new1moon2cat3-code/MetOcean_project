# 缺失圖片清單報告

> 產出日期：2026-06-07
> 範圍：`Output/*.md` + `Output/report.docx`
> 結論：**Output/ 目錄中無任何實體圖片檔案（零 PNG/JPG/JPEG/GIF/SVG/BMP）。以下 8 張圖 + 3 組設備照片均需由使用者手動插入。**

---

## 一、八張正式圖（有編號 placeholder）

| 圖號 | 標題 | 所屬章節 | 建議插入位置 | 實體檔案 | 類型 |
|:----:|------|:--------:|:------------:|:--------:|:----:|
| 圖 3-1 | 風成波形成機制示意圖 | 3.2.2 | 波浪形成理論文字之後 | ❌ 無 | 手繪示意圖 |
| 圖 3-2 | 波浪能通量與波高、週期之關係曲線圖 | 3.2.3 | 波浪能通量公式說明之後 | ❌ 無 | 數學函數曲線圖 |
| 圖 3-3 | OWC 工作原理示意圖 | 3.3.1 | 振盪水柱式 WEC 介紹之後 | ❌ 無 | 手繪示意圖 |
| 圖 3-4 | 點吸收式工作原理示意圖 | 3.3.2 | 點吸收式 WEC 介紹之後 | ❌ 無 | 手繪示意圖 |
| 圖 3-5 | 東北角海域波浪能開發潛力分布圖 | 3.5 | 波浪能資源評估總結之後 | ❌ 無 | Google Maps 底圖 + 疊加等值線 |
| 圖 6-1 | 測站配置總圖 | 6.5 | 測站配置方案論述之後 | ❌ 無 | Google Maps 衛星影像 + 標示 A–E 站 |
| 圖 6-2 | 系統架構圖 | 6.6 | 資料傳輸路徑說明之後 | ❌ 無 | 方塊流程圖（自行繪製） |
| 圖 6-3 | 研究區域位置圖（東北角索引圖） | 6.1 或 附錄 | 章節開頭或附錄 | ❌ 無 | 臺灣全島地圖 + 框選研究區域 |

---

## 二、設備照片（無正式圖號，但建議加入）

| 設備名稱 | 用途 | 實體檔案 | 建議來源 | 建議搜尋關鍵字 | 建議放入章節 |
|:---------|:-----|:--------:|:---------|:---------------|:-----------:|
| Datawell Directional Waverider MkIII | 波浪浮標外觀與部署示意 | ❌ 無 | Datawell 官方網站 | `Datawell Directional Waverider MkIII buoy photo` | 第五章 5.2.1 |
| Teledyne Sentinel V ADCP | 海流剖面儀設備外觀 | ❌ 無 | Teledyne Marine 官網 | `Teledyne Sentinel V ADCP 500kHz image` | 第五章 5.3.1 |
| Vaisala AWS310 | 岸基自動氣象站設備外觀 | ❌ 無 | Vaisala 官網 | `Vaisala AWS310 automatic weather station` | 第五章 5.4.1 |

---

## 三、其他提及但無圖號的視覺元素

| 項目 | 出處 | 說明 | 是否需要製作 |
|:-----|:----:|:-----|:-----------:|
| 建置期程甘特圖 | §9.7.2 | 文字敘述提到「甘特圖」但無正式圖號與 placeholder | 建議製作（9.7.2 節末尾） |
| 波高玫瑰圖 | 第十章 conclusion.md:72 | 建議作為後續研究工作 | 非必須（屬未來工作建議） |
| 月平均波高變化圖 | 第十章 conclusion.md:72 | 同上 | 非必須 |

---

## 四、逐圖製作建議

### 4.1 圖 3-1 — 波浪形成機制示意圖

| 項目 | 建議 |
|:-----|:------|
| 來源 | 手繪或學術論文示意圖 |
| 類型 | 斷面示意圖（風-浪交互作用） |
| 製作方式 | 自行繪製（PowerPoint / Illustrator / Draw.io） |
| 搜尋關鍵字 | `wind wave formation diagram`、`Jeffreys sheltering mechanism`、`wave generation schematic` |
| 替代方案 | 從 Wikipedia "Wind wave" 條目取得 CC 授權示意圖後改繪 |

### 4.2 圖 3-2 — 波浪能通量曲線圖

| 項目 | 建議 |
|:-----|:------|
| 來源 | 套公式自行繪製 |
| 類型 | XY 曲線圖（數學函數曲線族） |
| 製作方式 | Python Matplotlib：`P = 0.49 * Hs^2 * Te`，繪製 Hs=1,2,3,5m 四條曲線 |
| 搜尋關鍵字 | `wave energy flux vs period`、`wave power density curve` |
| 替代方案 | EMEC 網站有標準 wave energy flux 圖表可供參考改繪 |

### 4.3 圖 3-3 — OWC 工作原理示意圖

| 項目 | 建議 |
|:-----|:------|
| 來源 | 手繪或論文示意圖 |
| 類型 | 斷面結構示意圖 |
| 製作方式 | 自行繪製（標示空腔、水面振盪、Wells 渦輪機、發電機） |
| 搜尋關鍵字 | `OWC oscillating water column schematic`、`Wells turbine chamber diagram` |
| 替代方案 | 從 EMEC 或 academic papers（CC 授權）取得參考後改繪 |

### 4.4 圖 3-4 — 點吸收式工作原理示意圖

| 項目 | 建議 |
|:-----|:------|
| 來源 | 手繪或論文示意圖 |
| 類型 | 斷面結構示意圖 |
| 製作方式 | 自行繪製（標示浮體、液壓缸/直線發電機、錨繫系統、海底纜線） |
| 搜尋關鍵字 | `point absorber wave energy converter schematic`、`buoy type WEC diagram` |
| 替代方案 | 從 EMEC 或 Wikipedia 取得 CC 授權參考後改繪 |

### 4.5 圖 3-5 — 波浪能開發潛力分布圖

| 項目 | 建議 |
|:-----|:------|
| 來源 | Google Maps / CWA 資料疊加 |
| 類型 | 地理資訊圖（GIS 疊圖） |
| 製作方式 | ① 截取 Google Maps 衛星影像（東北角海域）<br>② 疊加波浪能通量等值線（kW/m）<br>③ 標示 A/B/C 測站位置 |
| 搜尋關鍵字 | `Taiwan northeast coast wave energy resource map`、`CWA Longdong buoy wave data` |
| 替代方案 | 自 CWA 龍洞浮標站數據計算年平均波浪能通量，用 QGIS 或 Python 繪製等值線圖 |

### 4.6 圖 6-1 — 測站配置總圖（最重要）

| 項目 | 建議 |
|:-----|:------|
| 來源 | Google Maps |
| 類型 | 衛星影像 + 標示 |
| 製作方式 | ① Google Maps 截取基隆–宜蘭頭城海岸衛星影像（比例尺 ~1:250,000）<br>② 插入彩色圖釘：A（紅）、B1/B2（藍）、C1/C2（綠）、D（綠）、E（橘）<br>③ 圖例說明各符號代表之設備類型 |
| 搜尋關鍵字 | Google Maps `基隆 鼻頭角 龍洞 三貂角` 衛星檢視 |
| 注意 | 需標示經緯度網格、比例尺、指北針 |

### 4.7 圖 6-2 — 系統架構圖

| 項目 | 建議 |
|:-----|:------|
| 來源 | 自行繪製 |
| 類型 | 方塊流程圖（network topology diagram） |
| 製作方式 | Draw.io / PowerPoint / Visio |
| 內容 | 各測站方塊 → 傳輸方式標示（4G LTE / Iridium / 有線）→ 匯入 E 站資料中心 → 資料庫 → 網頁展示平台 |
| 搜尋關鍵字 | `ocean observation system architecture diagram`、`data buoy network topology` |
| 替代方案 | 參考 NOAA NDBC 或 CWA 海氣象資料傳輸架構圖改繪 |

### 4.8 圖 6-3 — 研究區域索引圖

| 項目 | 建議 |
|:-----|:------|
| 來源 | Google Maps / 臺灣地圖 |
| 類型 | 位置索引圖（locator map） |
| 製作方式 | ① 臺灣全島地圖（或東北部地圖）<br>② 紅色矩形框選研究區域（24.5°N–25.2°N, 121.6°E–122.2°E）<br>③ 標示主要地名：基隆、鼻頭角、龍洞、三貂角、頭城 |
| 搜尋關鍵字 | `Taiwan northeast coast map`、`東北角地理位置圖` |

---

## 五、設備照片製作建議

| 設備 | 建議做法 | 替代方案 |
|:-----|:---------|:---------|
| Datawell Waverider MkIII | 官網下載產品照 + 自行繪製部署示意（浮標+錨繫+海底纜線） | 從 Datawell 型錄 PDF 截圖 |
| Sentinel V ADCP | Teledyne RDI 官網下載 | 從 Reference/Equipment 內之原廠 PDF 截圖 |
| Vaisala AWS310 | Vaisala 官網下載 | 從原廠型錄 PDF 截圖 |

---

## 六、總結

| 類別 | 數量 | 優先級 | 製作難度 |
|:-----|:----:|:------:|:--------:|
| **必須插入**（正式圖號） | 8 張 | ★★★★★ | 圖 3-2（曲線圖）可 Python 自動繪製；圖 3-1/3-3/3-4（示意圖）需手繪；圖 6-1（配置圖）最關鍵 |
| **建議加入**（設備照片） | 3 張 | ★★★☆☆ | 低——可從官網下載或從 PDF 截圖 |
| **可選**（甘特圖） | 1 張 | ★★☆☆☆ | 低——Word 或 Excel 即可製作 |
| **不須製作**（未來工作） | 2 項 | ☆☆☆☆☆ | 不屬於本報告主體 |
