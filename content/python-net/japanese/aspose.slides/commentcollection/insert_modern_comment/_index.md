---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentcollection/insert_modern_comment/
weight: 60
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposepydrawingpointf-datetime}
指定されたインデックスにコレクションへ新しいモダンコメントを挿入します。

### 戻り値

挿入されたモダンコメント。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | モダンコメントを挿入すべきコレクション内の要素のインデックスです。 |
| text | **str** | 新しいモダンコメントのプレーンテキストです。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | 新しいモダンコメントを追加するプレゼンテーション内のスライドです。 |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | 新しいモダンコメントが関連付けられるスライド上のシェイプです。 |
| position | **aspose.slides.PointF** | 新しいモダンコメントを追加するスライド上の位置です。 |
| creation_time | **DateTime** | モダンコメントの作成時刻です。 |

### 参照
* クラス [`CommentCollection`](/slides/python-net/ja/aspose.slides/commentcollection)
* クラス [`IModernComment`](/slides/python-net/ja/aspose.slides/imoderncomment)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)