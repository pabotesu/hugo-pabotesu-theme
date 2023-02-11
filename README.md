# hugo-pabotesu-theme

## 使い方
```
# サイトの作成
$ hugo new site -f yml new-site

$ cd new-site

# テーマの追加
$ git clone https://github.com/pabotesu/hugo-pabotesu-theme/ themes/hugo-pabotesu-theme

# テーマの追加(submodules)
git submodule add -b main https://github.com/pabotesu/hugo-pabotesu-theme  themes/hugo-pabotesu-theme

# サンプル設定ファイルのコピー
$ cp themes/hugo-pabotesu-theme/example.config.yml config.yml

# テンプレートファイルのコピー
$ cp themes/hugo-pabotesu-theme/archetypes/default.md archetypes/default.md

# 記事の作成
$ hugo new posts/test.md
```

## アーカイブの作成

`content/archives.md`

```
---
title: "Archives"
layout: "archive"
---
```

## 検索ページの作成(pagefindが必要です)

`content/search.md`

```
---
title: "Search"
layout: "search"
---
```

## Special Thanks
- https://github.com/minetaro12/hugo-osan-theme/
- https://github.com/feathericons/feather
