# 英打練習遊戲｜GitHub Pages 最終版

## 上傳方式

解壓縮後，將這裡面的 **所有內容** 上傳到 GitHub repository 的最外層。

正確結構：

```text
repository/
├── index.html
├── 版本一/
├── 版本二/
├── 版本三/
├── 版本四/
└── 版本五/
```

不要變成：

```text
repository/
└── 英打遊戲_GitHub可直接上傳_最終版/
    ├── index.html
    └── ...
```

## GitHub Pages

GitHub → repository → Settings → Pages

- Source：Deploy from a branch
- Branch：main
- Folder：/(root)
- Save

完成後網址通常為：

https://你的GitHub帳號.github.io/你的repository名稱/

## 本機測試

解壓縮後，直接雙擊最外層的 `index.html`。
首頁五個版本的連結使用相對路徑，不需要修改網址。

版本二的 `keyboard.png` 與 `beep.wav` 必須保留在：

版本二/assets/

內。
