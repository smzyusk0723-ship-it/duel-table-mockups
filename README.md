# DUEL TABLE 対戦卓UX 改修 — 設計モックアップ

確定済みUX課題ごとの「あるべき画面」を可視化した**設計見本（モックアップ）**です。実物の対戦アプリではなく、実装の設計見本。暗い対戦卓トーン・絵文字なし。

## まとめて見る（ここから全部開ける）

- **GitHub Pages**: https://smzyusk0723-ship-it.github.io/duel-table-mockups/
- **即時表示（githack）**: https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/index.html

## 個別（描画版・githack）

| 課題 | 内容 | 開く |
|---|---|---|
| 対戦中HUD | 通常ナビを対戦中だけ格納し、常時表示を「毎ターン触る8点」に絞る | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/battle-hud.html) |
| ドラッグ&ドロップ | 手札→各ゾーンの直接ドラッグ・ドロップ可ゾーン発光・失敗で戻る・Undo連動 | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/dnd.html) |
| 非公開情報モーダル | 山札/シールドを所有者で出し分け（自分だけ見る／公開する／手札へ） | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/hidden-info.html) |
| 横向きPWA | 下固定の操作バー・ドロワー・safe-area・横持ち自動判定の専用配置 | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/landscape-pwa.html) |
| 2ピック比較 | A/B 2枚組を同時比較・選択演出・導線分離（開始／設定） | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/twopick.html) |
| 明度階層・卓物体化 | 選択/手番/ドロップ先だけ発光・山札=束/墓地=捨て札束/シールド=伏せ5枚 | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/design-hierarchy.html) |
| 移動フィードバック | 移動先発光・短いトースト・飛ぶアニメ・枚数変化の強調 | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/move-feedback.html) |
| ログ詳細折りたたみ | ログタブでは選択カード詳細を折りたたみ、履歴の可読性を優先 | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/log-card-detail.html) |
| 離脱確認 | 対戦中に画面移動・新規対戦を押したときだけ確認を出す | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/leave-confirm.html) |
| 画像欠損・a11y | カード画像404時に名前＋種別へ退避・アイコンボタンにラベル | [開く](https://raw.githack.com/smzyusk0723-ship-it/duel-table-mockups/main/image-a11y.html) |

実装の正（仕様・受入条件）は非公開リポ `duel-masters-cgi` の `docs/20260620_実装プレイブック_設計.md`。
生成: 2026-06-20 / 多エージェント設計ワークフロー（12課題・うち10課題にモックアップ）。
