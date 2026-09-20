# AI 內容生成網頁樣板

測試文字內容

## 檔案結構

```text
ai-content-template
├─ index.html
├─ css
│  └─ style.css
├─ js
│  └─ script.js
└─ data
   └─ website-content.json
```

## 練習目標

- 看懂 `website-content.json` 需要哪些欄位。
- 使用 Gemini 產生 Hero、多筆特色內容與多組 FAQ。
- 將 AI 產出的 JSON 放回 `website-content.json`。
- 透過 `imageUrl` 與 `imageAlt` 加入網路圖片連結資料。
- 使用 Live Server 開啟頁面，確認多張卡片、多組 FAQ 與圖片是否正常顯示。

## 建議使用時機

- 第 2 節：先閱讀這份 README，觀察 `website-content.json` 的欄位格式，練習用提示詞要求 AI 輸出指定結構。
- 第 3 節：再將 `風格指引範例.md`、`website-content.json` 上傳或貼到 Gemini，練習讓 AI 參考檔案產出可替換的內容資料。
- 第 3 節圖片練習：預設 `website-content.json` 先不放圖片欄位，讓學員練習補上 `imageUrl` 與 `imageAlt` 後，再重新整理網頁觀察圖片是否出現。

## 課堂範例圖片網址

如果課堂中暫時找不到合適圖片，可以先使用以下範例網址練習。這些網址可以直接放入 `features` 的 `imageUrl` 欄位：

```text
圖片 1：https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=900&q=80
圖片 2：https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=900&q=80
圖片 3：https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=900&q=80
```


## 檢查清單

- JSON 是否使用雙引號？
- 每個欄位名稱是否和樣板一致？
- `features` 是否是陣列？
- `faq` 是否是陣列？
- 每筆特色是否都有 `title` 和 `description`？
- 如果有加入圖片，每筆特色是否都有 `imageUrl` 和 `imageAlt`？
- 圖片網址是否可以在瀏覽器開啟？
- `imageAlt` 是否能說明圖片內容？
- 每組 FAQ 是否都有 `question` 和 `answer`？
- 使用 Live Server 開啟後，畫面是否正常顯示？
- Console 是否有錯誤訊息？

從電腦新增的文字。