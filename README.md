# EULER-Ω 終極擴增實境工作室 PWA

這是一個可直接部署至 GitHub Pages 的完整 PWA 專案。

## 功能

- 前後鏡頭切換
- 鏡像模式
- MediaPipe Holistic 人體辨識
- 臉部網格
- 手部網格
- 姿態骨架
- Delaunay 三角網格
- 圖片與影片背景
- 色調、亮度、飽和度、對比度、暈影
- 語音字幕
- PNG 截圖
- WebM 錄影
- 本機設定儲存
- PWA 安裝
- Service Worker 離線快取
- GitHub Pages 自動部署

## 本機測試

在專案資料夾開啟 PowerShell：

```powershell
py -m http.server 8080
```

電腦瀏覽器開啟：

```text
http://localhost:8080
```

注意：手機不可輸入手機自己的 `localhost` 連電腦。

## GitHub Pages 網址

```text
https://qhero70.github.io/EULER-OMEGA-AR-Studio/
```

## iPhone 安裝

1. 使用 Safari 開啟 GitHub Pages 網址。
2. 點擊分享。
3. 點擊「加入主畫面」。

## Android 安裝

1. 使用 Chrome 開啟 GitHub Pages 網址。
2. 點擊畫面上的「安裝 App」，或右上角選單。
3. 選擇「安裝應用程式」。

## 重要限制

- 鏡頭必須在 HTTPS 或電腦本機 localhost 下使用。
- MediaPipe 第一次載入必須有網路。
- iPhone 對 WebM 下載與網頁語音辨識支援可能受系統版本限制。
- 錄影目前只錄製 AR 畫布，不含麥克風聲音。
