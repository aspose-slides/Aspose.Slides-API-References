---
title: remove method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/icommentcollection/remove/
weight: 60
---
## remove(self, comment) {#icomment}
コレクション内の指定されたコメントの最初の出現を削除します。

```python
def remove(self, comment):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/ja/aspose.slides/icomment) | コレクションから削除するコメントです。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | コメントが `None` の場合 |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | コメントがすでに削除されている場合にスローされます。 |

### 参照
* クラス [`IComment`](/slides/python-net/ja/aspose.slides/icomment)
* クラス [`ICommentCollection`](/slides/python-net/ja/aspose.slides/icommentcollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)