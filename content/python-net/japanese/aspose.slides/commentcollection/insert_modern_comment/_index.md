---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentcollection/insert_modern_comment/
weight: 60
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposeslidespointf-datetime}
指定されたインデックスにコレクションに新しいモダンコメントを挿入します。

### 戻り値

挿入されたモダンコメント。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | コレクション内でモダンコメントを挿入すべき要素のインデックス。 |
| text | **str** | 新しいモダンコメントのプレーンテキスト。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | 新しいモダンコメントを追加するプレゼンテーション内のスライド。 |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | 新しいモダンコメントが関連付けられるスライド上のシェイプ。 |
| position | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | 新しいモダンコメントを追加するスライド上の位置。 |
| creation_time | **DateTime** | モダンコメントの作成時刻。 |

### 参照
* クラス [`CommentCollection`](/slides/python-net/ja/aspose.slides/commentcollection)
* クラス [`IModernComment`](/slides/python-net/ja/aspose.slides/imoderncomment)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`PointF`](/slides/python-net/ja/aspose.slides/pointf)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)