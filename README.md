# STELLA 國中 7 上自然第 2 章：3D 互動教學微縮群島 (WebGL / Three.js)

> 🚀 **雲端正式直連網址（免安裝直開）：**  
> [https://pwb6331-hub.github.io/stella-science-island-ch2/](https://pwb6331-hub.github.io/stella-science-island-ch2/)

結合 WebGL／Three.js 創意微縮模型美學（Tilt-shift Miniature & Clay Aesthetic）與太陽系 9 大天體背景巡航系統，依據國中七年級上學期自然第 2 章「生物體的能量與代謝」製作之 3D 沉浸式自主探究教學群島。

## 🌟 四大島嶼單元與內容模組
1. **2-1 養分與能量：** 六大養分產能計算、卡計原理、碘液與本氏液隔水加熱實驗檢測。
2. **2-2 酵素催化：** 代謝作用、酵素四大特性（專一性鎖鑰模型）、溫度高溫永久變性與 pH 活性曲線。
3. **2-3 光合作用：** 葉片微觀解剖、光反應 vs 碳反應物質能量流動、光合作用產物檢驗四部曲。
4. **2-4 消化與吸收：** 單向管狀消化道、五大消化腺與消化液、小腸絨毛微血管與乳糜管吸收分工。
5. **STELLA 核心：** 科學 (S)、科技 (T)、工程 (E)、藝術美感 (A)、語文倡議 (LA) 全方位跨學科探究。

## ⚡ WebGL 旗艦級效能優化
- **幾何體與材質池化共享 (GeoCache & MatCache)：** 徹底複用網格，大幅縮減 Draw Calls。
- **幀率無關時間步進 (Frame-rate Independent Timing)：** 引入 `THREE.Clock` delta 控制行星公轉與鏡頭指數阻尼平滑滑翔。
- **無外部依賴 Web Audio API 音效引擎：** 原生合成點擊音、正解琶音與彩花慶祝。
