# sijibun

Claudeの「プロジェクトの指示」にコピペして使う指示文の配布サイトです。
公開URL: https://sorafjah.github.io/sijibun/

## 指示文を追加・更新するには

1. `texts/` フォルダの `.txt` ファイルに、指示文をそのまま貼りつけます。
   - 先頭が `【準備中】` のあいだは「じゅんび中」と表示され、コピーできません。
2. 新しい指示文を増やすときは、`texts/index.json` に項目（title / badge / desc / file）を1つ足します。
3. GitHubにコミットすると、数分でサイトに反映されます。

## 構成

- `index.html` … サイト本体（1ファイル）
- `texts/index.json` … 掲載する指示文の一覧
- `texts/*.txt` … 指示文の本文
- `.nojekyll` … Jekyllを使わずそのまま公開するための印
