# wit-smart-price
# PROJECT: wit-smart-price

## 概要
- 目的：価格比較/価格ログ/通知など（SmartPrice系）
- 形態：Web / GAS / Firebase（予定含む）

## 重要リンク（あとで埋める）
- GitHub（正本）：https://github.com/wit-ai-apps/wit-smart-price
- GAS編集URL：
- 配布URL（必ず ?b=BUILD_ID）：
- Firebase（Project/Console）：
- 重要ID（Spreadsheet/Driveなど）：

## UI凍結ルール（最重要）
- UI（見た目）は完全固定（変更禁止）：
  - HTML構造 / 文言 / 配置 / サイズ / 色 / 余白 / クラス名
- 変更してよいのは「内部処理（ロジック）」のみ
- UI差分が出た場合は **差し戻し** を優先する

## 版管理ルール（固定）
- VERSION：vX.Y.Z
- BUILD_ID：YYYY-MM-DD_HHMM_<tag>
- 配布URL：必ず `?b=BUILD_ID`（検証のみ `&debug=1`）

## 変更依頼の合言葉（Rex/Gemini/ユイ共通）
- 依頼文の先頭に必ず書く：  
  **「UI凍結で、中身だけ。UI差分が出たら差し戻し。」**
