# A2O 知識問答機器人

單頁 HTML 知識問答，使用 A2O（虛構）內部政策知識庫（2026 版新人須知、報價流程、退換貨辦法），並透過 **Groq API** 驅動 LLM 回答。

## 功能
- 單一 `index.html`，無需後端伺服器
- 質感深色聊天介面
- 使用者輸入 **Groq API Key** 後才能使用（Key 儲存在瀏覽器 localStorage）
- 僅依知識庫回答，知識庫未涵蓋時會提示以主管/相關單位為主

## 取得 Groq API Key
1. 前往 https://console.groq.com
2. 註冊並建立 API Key（`gsk_...`）

## 使用
直接開啟 `index.html`，輸入 API Key → 儲存 → 開始問答。

## 部署到 GitHub Pages（方式 A）
1. 在 GitHub 建立新倉庫（Public）
2. **Add file → Upload files**，上傳本資料夾的 `index.html` 與 `README.md`
3. 進 **Settings → Pages** → Source 設為 `Main / root`
4. 完成後網址為 `https://<你的帳號>.github.io/a2o-kb-chat/`

## 授權
練習用途，知識庫內容為課程假資料。
