# 📡 RSS リーダー表示テスト用フィード

RSSリーダーアプリの表示確認・動作テストを目的としたサンプルデータです。
記事の内容は**すべて架空のもの**であり、実在する人物・団体・出来事とは一切関係ありません。

---

## 📁 ファイル構成

```
rss-test-feed/
├── README.md          # このファイル
├── feed.xml           # RSS 2.0 フィード本体（45記事）
└── images/            # 記事サムネイル画像
    ├── quantum_communication.png   # 記事1用
    ├── floatonium_alloy.png        # 記事2用
    ├── galactic_contest.png        # 記事3用
    ├── mars_weather.png            # 記事4用
    ├── infinity_energy.png         # 記事5用
    └── time_travel_podcast.png     # 記事6用
```

## 📋 記事一覧とテストパターン

各記事は特定の表示パターンをテストするために設計されています。

### 読み込む

```
https://ryo08271154.github.io/rss-test-feed/feed.xml
```

## ⚠️ 注意事項

- このフィードの記事内容は**すべて架空のフィクション**です
- URLには実在しない `.test` ドメインを使用しています（RFC 2606 準拠）
- 実際のRSS配信には使用しないでください
- テスト・開発・学習目的のみにご利用ください
