---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
指定されたインデックスの要素をコレクションから削除します。


```python
def remove_at(self, index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 削除する要素のゼロベースインデックスです。 |

### 備考

1) PptxEditException のスローを回避するために、事前に layout の HasDependingSlides プロパティをチェックしてください。  
2) コードを簡素化するために、[`ILayoutSlide.remove`](/slides/python-net/ja/aspose.slides/ilayoutslide/remove) メソッドも使用できます。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | レイアウトがプレゼンテーションで使用されている場合にスローされます（HasDependingSlides プロパティが true の場合）。 |

### 参照
* クラス [`IMasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)