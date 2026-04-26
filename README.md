# 香蕉記帳 隱私權政策

本 repo 僅用於託管 [香蕉記帳](https://github.com/paul870325-tech/Banana-Finance) APP 的隱私權政策。

**線上版本（GitHub Pages，使用 Jekyll cayman 主題渲染）：**
https://paul870325-tech.github.io/banana-finance-privacy/

---

## 架構

- **單一來源**位於主 project：`app/assets/legal/privacy_policy.md`
  - App 內透過 `flutter_markdown` 套件渲染顯示
  - 透過 `sync-privacy.bat` 同步本 repo 的 `index.md`
  - 由 GitHub Pages + Jekyll 渲染為 HTML
- 本 repo **不要直接編輯 index.md**，請改主 project 的 `app/assets/legal/privacy_policy.md` 後跑 sync-privacy.bat

## 檔案說明

| 檔案 | 用途 |
|---|---|
| `index.md` | 隱私權政策內容（自動同步，勿手動編輯） |
| `_config.yml` | Jekyll 主題與站台設定 |
| `README.md` | 本說明 |
