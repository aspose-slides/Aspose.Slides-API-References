---
title: remove method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
コレクションからレイアウトを削除します。

```python
def remove(self, value):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | コレクションから削除するレイアウトスライド。 |

### Remarks

1) PptxEditException のスローを防ぐために、事前にレイアウトの HasDependingSlides プロパティを確認してください。  
2) コードを簡略化するために [`ILayoutSlide.remove`](/slides/python-net/ja/aspose.slides/ilayoutslide/remove) メソッドも使用できます。

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | レイアウトがプレゼンテーションで使用されている場合にスローされます (HasDependingSlides プロパティが true)。 |

### See Also
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`LayoutSlideCollection`](/slides/python-net/ja/aspose.slides/layoutslidecollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)