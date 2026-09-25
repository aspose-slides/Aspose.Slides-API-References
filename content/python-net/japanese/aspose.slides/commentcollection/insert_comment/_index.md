---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentcollection/insert_comment/
weight: 50
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposeslidespointf-datetime}
指定されたインデックスに新しいコメントをコレクションに挿入します。

### 戻り値

挿入されたコメント。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | コレクション内でコメントを挿入すべき要素のインデックス。 |
| text | **str** | 新しいコメントのプレーンテキスト。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | コメントを追加するプレゼンテーション内のスライド。 |
| position | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | コメントを追加するスライド上の位置。 |
| creation_time | **DateTime** | コメント作成の時刻。 |

### 参照
* クラス [`CommentCollection`](/slides/python-net/ja/aspose.slides/commentcollection)
* クラス [`IComment`](/slides/python-net/ja/aspose.slides/icomment)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`PointF`](/slides/python-net/ja/aspose.slides/pointf)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)