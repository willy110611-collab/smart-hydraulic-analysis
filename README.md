<p align="center"><img src="assets/gw_logo.png" width="320" alt="GW"></p>

# 智慧水理分析

HEC-RAS 中文操作工作台（Designed by CHEN-KUAN-WEI）。

用中文介面開啟 HEC-RAS 專案、修改斷面與構造物、交給 HEC-RAS 計算、比較方案、審查與產出送審報告。
**所有水理數值一律由 HEC-RAS 計算**，工作台只負責讀取、顯示與整理；工作台自行換算的數字會標示「工作台換算」。

## 下載
到右側 **Releases** 下載最新的 `SmartHydraulicAnalysis_Setup_<版本>.exe`（例：`SmartHydraulicAnalysis_Setup_2026.11.2.2.exe`）。
檔名用英文是因為 GitHub 不接受中文附件檔名；安裝後的程式名稱與桌面捷徑仍是「智慧水理分析」。

## 安裝前請先準備
| 程式 | 必要 | 說明 |
|---|---|---|
| HEC-RAS 6.6（或 7.0.x） | ✅ | 美國陸軍工兵團 HEC 免費軟體：https://www.hec.usace.army.mil/software/hec-ras/download.aspx |
| Microsoft Edge | ✅ | Windows 10／11 內建 |
| Microsoft Word | 選用 | 報告轉 PDF |
| ODA File Converter | 選用 | 讀取 DWG（DXF 不需要） |

不需要 Python、ArcGIS 或任何帳號；沒有網路也能使用（只有檢查更新時會連網，且只讀取 GitHub 的版本資訊，不傳送任何資料）。

## 安裝步驟
1. 先安裝 HEC-RAS。
2. 執行安裝程式；若 Windows 顯示「已保護您的電腦」，點「其他資訊 → 仍要執行」（安裝程式尚未購買數位簽章）。
3. 從桌面開啟「智慧水理分析」。沒有資料可先按「📦 開啟範例專案」試用。

工作台開啟專案時會先複製到工作資料夾，**不會修改你的原始 HEC-RAS 檔案**。

## 授權
HEC-RAS 為美國政府公共軟體，需由使用者自行安裝。第三方元件授權列於安裝後的「說明 → 關於」。
