# 巧 / AI制作・個人開発ポートフォリオ

個人開発者「巧」の独立した静的ポートフォリオサイト。

## 事実確認と公開方針

- 「ツール棚」：`takkun-studio/tool-shelf` の `README.md` と `src/lib/tools.ts` から実装済み10ツールを確認。
- 「lelien デジタルサポート」：`takkun-studio/lelien-digital-support` の公開ページソースを確認。
- 「修理カルテ」：Supabase 上の `lelien-repair` プロジェクトを確認。顧客情報や非公開管理画面は掲載しない。
- 「ローカル画像生成ワークフロー」「カワウソのゲーム企画」「診断エンジン」：公開されていないものは公開リンクを付けず、進捗を明示。
- 画像は各領域のために制作したオリジナルの概念イラスト。アプリ画面や成果画像そのものではない。
- GitHubアカウントの非公開情報や私用メールアドレスは掲載しない。

## 内容を更新する

`content/projects.js` に作品を1件追加・編集するだけ。公開リンクが確認できるまでは `link: null`。

## ローカル確認

```sh
python3 -m http.server 8788
```

## Cloudflare Pages

- フレームワーク：None
- ビルドコマンド：空欄（必須の場合は `exit 0`）
- 出力ディレクトリ：`.`
- Production ブランチ：`main`
- ルートディレクトリ：`/`

既存の `lelien-digital-support`、`tool-shelf`、その他のリポジトリ／設定には変更しない。
