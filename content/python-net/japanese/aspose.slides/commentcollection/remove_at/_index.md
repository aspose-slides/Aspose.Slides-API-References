---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentcollection/remove_at/
weight: 80
---
## remove_at(self, index) {#int}
コレクション内の指定されたインデックスにある要素を削除します。


```python
def remove_at(self, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 削除する要素のゼロベースインデックスです。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | インデックスが 0 未満、または Count 以上です |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | コメントがすでに削除されている場合にスローされます。 |



### 参照
* クラス [`CommentCollection`](/slides/python-net/ja/aspose.slides/commentcollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)