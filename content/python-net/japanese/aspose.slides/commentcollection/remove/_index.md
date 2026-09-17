---
title: remove method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentcollection/remove/
weight: 70
---
## remove(self, comment) {#icomment}
指定されたコメントの最初の出現をコレクションから削除します。


```python
def remove(self, comment):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/ja/aspose.slides/icomment) | コレクションから削除するコメントです。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | comment が `None` の場合 |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | comment が既に削除されている場合にスローされます。 |



### 参照
* クラス [`CommentCollection`](/slides/python-net/ja/aspose.slides/commentcollection)
* クラス [`IComment`](/slides/python-net/ja/aspose.slides/icomment)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)