---
title: remove method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
レイアウトをプレゼンテーションから削除します。

```python
def remove(self):
    ...
```

### 備考
PptxEditException のスローを防ぐために、事前に layout の HasDependingSlides プロパティをチェックしてください。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | レイアウトがすでにプレゼンテーションから削除されているか、プレゼンテーションで使用されている場合（その HasDependingSlides プロパティが true の場合）にスローされます。 |

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)