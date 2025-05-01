# Two-Player Shooting Game

## 遊戲介紹
這是一款簡單的雙人射擊遊戲，玩家需要控制角色移動並射擊對手。遊戲中包含 AI 對手，玩家需要在 AI 的攻擊下生存並擊敗 AI。遊戲還整合了 Gemini API。

### 遊戲特色
- **雙人對戰**：玩家與 AI 進行射擊對戰。
- **即時更新**：顯示玩家與 AI 的生命值。

## 使用方式

### 1. 啟動遊戲
1. 確保您已安裝現代瀏覽器（如 Google Chrome 或 Firefox）。
2. 打開 `0505.index.html` 檔案，即可啟動遊戲。

### 2. 操作方式
- **移動角色**：將滑鼠移動到畫布內，角色會跟隨滑鼠的垂直位置移動。
- **射擊**：點擊滑鼠左鍵，發射子彈攻擊 AI。

### 3. 遊戲目標
- 玩家需要擊中 AI，將其生命值減至 0。
- 避免被 AI 的子彈擊中，保護自己的生命值。

### 4. Gemini API 整合
- 遊戲會每 10 秒自動更新一次 BTC/USD 的最新價格，顯示在畫面左上角的資訊欄中。

## 開發者指南

### 1. 修改 Gemini API 金鑰
請將 `0505.index.html` 檔案中的 `geminiApiKey` 替換為您的實際 API 金鑰：
```javascript
const geminiApiKey = 'YOUR_GEMINI_API_KEY';
```

### 2. 修改 Gemini API URL
如果需要查詢其他交易對，請修改 `geminiApiUrl`：
```javascript
const geminiApiUrl = 'https://api.gemini.com/v1/pubticker/交易對';
```

### 3. 本地開發
1. 使用任何 HTTP 伺服器（如 VS Code 的 Live Server 擴展）啟動專案。
2. 確保網路連線正常，以便與 Gemini API 通信。

## 注意事項
- 請勿將您的 API 金鑰暴露在公開的程式碼庫中。
- 如果您不需要 Gemini API 整合，可以移除相關程式碼。

## 聯絡方式
如果您有任何問題或建議，請聯絡開發者。

- Email: [example@example.com](mailto:example@example.com)
- GitHub: [YourGitHubProfile](https://github.com/YourGitHubProfile)
