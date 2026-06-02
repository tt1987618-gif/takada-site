# GitHub Pages 公開手順

このフォルダは、そのまま `GitHub Pages` に公開できる構成です。

## 公開方法

1. GitHub で新しいリポジトリを作成する
2. この `recreated-site` フォルダの中身を、そのリポジトリの直下に置く
3. GitHub にアップロードする
4. GitHub の `Settings` → `Pages` を開く
5. `Deploy from a branch` を選ぶ
6. Branch を `main`、Folder を `/ (root)` にする
7. 数分待つ

公開URLの例:

- `https://あなたのユーザー名.github.io/リポジトリ名/`

## このサイトに含まれているファイル

- `index.html`
- `ai-consulting.html`
- `sns-consulting.html`
- `training.html`

## 公開前の補足

- ページ同士のリンクは相対パスなので、そのまま動きます
- `.nojekyll` を入れてあるので、GitHub Pages 側で余計な変換が入りません

## 独自ドメインをつなぐ場合

あとで独自ドメインをつなぐなら、GitHub Pages の `Custom domain` に設定して、DNS に `CNAME` か `Aレコード` を追加します。

## いちばん簡単なアップロード方法

もし GitHub Desktop を使うなら、

1. 新規リポジトリを作る
2. このフォルダの中身を入れる
3. `Commit`
4. `Publish repository`

で進められます。
