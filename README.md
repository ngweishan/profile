# 黃韋姍 — 藍紫泡泡風個人履歷網站

響應式單頁履歷網站，純 HTML / CSS / JavaScript，無需安裝套件或建置流程。使用個人履歷圖片中的照片與作品集 QR Code。

## 本機預覽

直接使用瀏覽器開啟 `index.html` 即可。若使用 VS Code，也可以安裝 Live Server 預覽。

## GitHub Pages 部署

1. 在 GitHub 建立新的 **Public** repository（例如 `wei-shan-resume`）。
2. 將 **index.html、styles.css、script.js、assets/** 四個項目上傳至 repository 根目錄；不要只上傳 ZIP。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**，選取 `main` 與 `/(root)`，按 **Save**。
5. GitHub Pages 發布後，網站網址通常為 `https://你的GitHub帳號.github.io/wei-shan-resume/`。

> 注意：姓名、電子郵件、手機號碼及照片會公開於網站，發布前請確認是否願意公開。

## 修改內容

- 文字、學業成績及經歷：修改 `index.html`。
- 色彩、字體、泡泡效果：修改 `styles.css`。
- 個人照片：替換 `assets/profile.png`。
- 作品集連結：搜尋 `https://reurl.cc/Ab1OVe` 並替換為你的作品集網址；如果連結改了，請記得同步更換 `assets/portfolio-qr.png`。

網站已針對手機螢幕與偏好降低動態效果的使用者進行優化。
