---
title: remove method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
コレクションからレイアウトを削除します。

```python
def remove(self, value):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | コレクションから削除するレイアウト スライド。 |

### 備考

1) PptxEditException のスローを回避するために、事前にレイアウトの HasDependingSlides プロパティを確認してください。
2) コードを簡略化するために、[`ILayoutSlide.remove`](/slides/python-net/ja/aspose.slides/ilayoutslide/remove) メソッドを使用することもできます。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | プレゼンテーションでレイアウトが使用されている場合にスローされます（HasDependingSlides プロパティが true の場合）。 |

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`MasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)