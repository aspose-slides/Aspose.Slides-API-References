---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icommentcollection/insert_comment/
weight: 40
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposepydrawingpointf-datetime}
コレクションの指定されたインデックスに新しいコメントを挿入します。

### 戻り値

挿入されたコメント。

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | コレクション内の要素のインデックスで、コメントを挿入すべき位置です。 |
| text | **str** | 新しいコメントのプレーンテキスト。 |
| slide | [`ISlide`](/slides/python-net/ja/aspose.slides/islide) | 新しいコメントを追加するプレゼンテーション内のスライド。 |
| position | **aspose.slides.PointF** | 新しいコメントを追加するスライド上の位置。 |
| creation_time | **DateTime** | コメントが作成された時間。 |

### 参照
* クラス [`IComment`](/slides/python-net/ja/aspose.slides/icomment)
* クラス [`ICommentCollection`](/slides/python-net/ja/aspose.slides/icommentcollection)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)