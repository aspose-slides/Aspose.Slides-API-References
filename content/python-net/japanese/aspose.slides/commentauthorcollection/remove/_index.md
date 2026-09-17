---
title: remove method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/commentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
コレクションから指定された author の最初の出現を削除します。

```python
def remove(self, author):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor) | コレクションから削除する author。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Author は `None` |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | author がすでに削除されている場合にスローされます。 |

### 参照
* クラス [`CommentAuthorCollection`](/slides/python-net/ja/aspose.slides/commentauthorcollection)
* クラス [`ICommentAuthor`](/slides/python-net/ja/aspose.slides/icommentauthor)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)