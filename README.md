# 画像情報処理システム研究室（宮崎研究室）ウェブサイト

GitHub Pages（Jekyll）で公開する研究室サイトです。

## ファイル構成

| ファイル | 内容 |
|---|---|
| `_config.yml` | サイト名、連絡先、researchmap・大学ページ・読話クラブなどのリンク（業績はresearchmapに一本化） |
| `index.html` | トップページ（研究室について・研究紹介・ニュース・教員紹介・学生の皆さんへ） |
| `research/index.html` | 研究紹介 |
| `news/index.html` | ニュース一覧（自動で作られます） |
| `_posts/` | ニュースの記事（1件 = 1ファイル） |
| `en/index.html` | 英語ページ |
| `_includes/pixel-grid.html` | トップの模様 |
| `assets/css/style.css` | デザイン |

## ニュースを追加するには

`_posts/` に、`年-月-日-英数字の名前.md` という名前のファイルを追加します。

例：`_posts/2026-11-05-conference.md`

```
---
layout: post
title: 情報処理学会の研究会で発表しました
category_label: 学会発表
---

本文をここに書きます。
```

`category_label` には「学会発表」「受賞」「外部資金」など、日付の横に表示するラベルを書きます。保存（コミット）すると、1〜2分でサイトに反映されます。

## 公開前に直す箇所

現在、未入力の箇所はありません。ORCIDを載せる場合は `_config.yml` の `orcid` にURLを記入してください。
