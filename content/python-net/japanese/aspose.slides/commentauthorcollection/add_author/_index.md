---
title: add_author method
second_title: Python 用 Aspose.Slides の .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentauthorcollection/add_author/
weight: 10
---
## add_author(self, name, initials) {#str-str}
コレクションの末尾に新しい著者を追加します。

### 戻り値

新しい [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor) オブジェクト。



```python
def add_author(self, name, initials):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| name | **str** | 新しい著者の名前。 |
| initials | **str** | 新しい著者のイニシャル。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | 同じ名前とイニシャルを持つ著者がすでに追加されている場合にスローされます。 |



### 参照
* クラス [`CommentAuthorCollection`](/slides/python-net/ja/aspose.slides/commentauthorcollection)
* クラス [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)