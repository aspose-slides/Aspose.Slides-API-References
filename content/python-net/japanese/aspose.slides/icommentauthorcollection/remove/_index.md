---
title: remove method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/icommentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
コレクション内の指定された author の最初の出現を削除します。

```python
def remove(self, author):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor) | コレクションから削除する author です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Author は `None` です |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | author がすでに削除されている場合にスローされます。 |

### 参照
* class [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor)
* class [`ICommentAuthorCollection`](/slides/python-net/ja/aspose.slides/icommentauthorcollection)
* class [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)