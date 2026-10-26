---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icommentcollection/insert_comment/
weight: 40
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposeslidespointf-datetime}
コレクションの指定したインデックスに新しいコメントを挿入します。

### 戻り値

挿入されたコメント。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | コメントを挿入すべきコレクション内の要素のインデックス。 |
| text | **str** | 新しいコメントのプレーンテキスト。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | 新しいコメントを追加するプレゼンテーション内のスライド。 |
| position | [`PointF`](/slides/python-net/ja/aspose.slides/pointf) | コメントを追加するスライド上の位置。 |
| creation_time | **DateTime** | コメント作成の時刻。 |

### 参照
* クラス [`IComment`](/slides/python-net/ja/aspose.slides/icomment)
* クラス [`ICommentCollection`](/slides/python-net/ja/aspose.slides/icommentcollection)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`PointF`](/slides/python-net/ja/aspose.slides/pointf)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)