---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentcollection/insert_comment/
weight: 50
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposepydrawingpointf-datetime}
指定したインデックスに新しいコメントをコレクションに挿入します。

### Returns
挿入されたコメント。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | コメントを挿入すべきコレクション内の要素のインデックス。 |
| text | **str** | 新しいコメントのプレーンテキスト。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | 新しいコメントを追加するプレゼンテーション内のスライド。 |
| position | **aspose.slides.PointF** | コメントを追加するスライド上の位置。 |
| creation_time | **DateTime** | コメント作成の時間。 |

### See Also
* クラス [`CommentCollection`](/slides/python-net/ja/aspose.slides/commentcollection)
* クラス [`IComment`](/slides/python-net/ja/aspose.slides/icomment)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)