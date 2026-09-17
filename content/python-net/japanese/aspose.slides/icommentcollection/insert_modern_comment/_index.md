---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icommentcollection/insert_modern_comment/
weight: 50
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposepydrawingpointf-datetime}
指定されたインデックスでコレクションに新しいモダンコメントを挿入します。

### 戻り値

挿入されたモダンコメント。

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | Index of the element in a collection at which modern comment should be inserted. |
| text | **str** | Plain text of a new modern comment. |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [`IShape`](/slides/python-net/ja/aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | **aspose.slides.PointF** | Position on a slide where to add a new modern comment. |
| creation_time | **DateTime** | Time of a modern comment creation. |

### 参照
* クラス [`ICommentCollection`](/slides/python-net/ja/aspose.slides/icommentcollection)
* クラス [`IModernComment`](/slides/python-net/ja/aspose.slides/imoderncomment)
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)