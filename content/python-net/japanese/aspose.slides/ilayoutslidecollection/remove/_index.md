---
title: remove method
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
コレクションからレイアウトを削除します。

```python
def remove(self, value):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | コレクションから削除するレイアウト スライド。 |

### 備考

1) PptxEditException のスローを回避するために、事前にレイアウトの HasDependingSlides プロパティを確認してください。  
2) コードを簡略化するために、[`ILayoutSlide.remove`](/slides/python-net/ja/aspose.slides/ilayoutslide/remove) メソッドも使用できます。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | プレゼンテーションでレイアウトが使用されている場合にスローされます（HasDependingSlides プロパティが true の場合）。 |

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`ILayoutSlideCollection`](/slides/python-net/ja/aspose.slides/ilayoutslidecollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)