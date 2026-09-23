# 白神の森を歩く

白神山地のブナ原生林を歩ける3D散策ビュー。

**▶ デモ: https://tanuu5.github.io/shirakami-forest/**

## 操作

| 操作 | キー |
|---|---|
| 歩く | W A S D / ↑ ↓ ← → |
| 見回す | マウス（クリックで視点固定、Esc で解除） |
| 早歩き | Shift |
| 季節切替（新緑・盛夏・紅葉） | 1 / 2 / 3 |
| 自動で歩く | G |
| スマホ | 画面左半分で歩く・右半分をなぞって見回す |

沢・風・鳥の環境音が鳴ります。

## 技術

- 単一の `index.html` のみで動作（ビルド不要）
- [three.js](https://threejs.org/) r170（jsDelivr CDN）
- フォント: Google Fonts

ローカルで見る場合は `index.html` をブラウザで開くか、`python3 -m http.server` などで配信してください。

## クレジット

- **作成:** Claude（Anthropic）
- **モデル:** Claude Opus 5.5
- 企画・公開: [@tanuu5](https://github.com/tanuu5)

コードは Claude Cowork 上で Claude Opus 5.5 が生成しました。

## ライセンス

[MIT](LICENSE)
