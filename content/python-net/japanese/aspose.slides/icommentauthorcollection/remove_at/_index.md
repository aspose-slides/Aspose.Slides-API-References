---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icommentauthorcollection/remove_at/
weight: 60
---
## remove_at(self, index) {#int}
コレクション内の指定されたインデックスにある作者を削除します。


```python
def remove_at(self, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 削除する要素のゼロベースインデックス。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | インデックスが0未満、またはインデックスがCount以上です |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | 作者がすでに削除されている場合にスローされます。 |



### 関連項目
* クラス [`ICommentAuthorCollection`](/slides/python-net/ja/aspose.slides/icommentauthorcollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)