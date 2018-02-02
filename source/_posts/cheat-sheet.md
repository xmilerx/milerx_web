---
title: Markdownのチートシート
date: 2018-02-02 01:10:19
tags:
- Markdown
category: Technology
thumbnail: /img/2018/2018-02-02/markdown.png
---
このブログはhexoという静的サイトジェネレーターで作っています。

ホスティングにはnetlifyというサービスを使っています。

hexoはnode.jsで動く静的サイトジェネレータなんですが、markdown記法で記述していかないといけません。markdownよく忘れるのでここに備忘録として書いておこうと思います。
<!-- more -->
***
# 見出し
## h2 見出し
### h3 見出し
#### h4 見出し
##### h5 見出し
###### h6 見出し

# 装飾
**太字** `**太字**`
*イタリック* `*イタリック*`
~~取消線~~ `~~取消線~~`
<u>下線</u> `<u>下線</u>`

# 画像
`![代替文字](URL "タイトル")`


# hexo独自
## read more
`<!-- more -->`

## table of contents
hexo-tocが必要

## 動画埋め込み
`｛% youtube id %｝`
`｛% vimeo id %｝`

## twitter
`｛% twitter URL %｝`
hexo-tag-twitterが必要。
{% twitter https://twitter.com/x_miler/status/959232913995952128 %}
