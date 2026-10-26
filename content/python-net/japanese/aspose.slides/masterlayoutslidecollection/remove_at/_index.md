---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
コレクションの指定されたインデックスにある要素を削除します。

```python
def remove_at(self, index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 削除する要素のゼロベースインデックスです。 |

### 備考

1) PptxEditException のスローを防ぐために、事前にレイアウトの HasDependingSlides プロパティを確認してください。  
2) コードを簡略化するために [`ILayoutSlide.remove`](/slides/python-net/ja/aspose.slides/ilayoutslide/remove) メソッドも使用できます。

### 例外

| 例外 | 説明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception) | レイアウトがプレゼンテーションで使用されている場合にスローされます (HasDependingSlides プロパティが true の場合)。 |

### 参照
* クラス [`MasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection)
* クラス [`PptxEditException`](/slides/python-net/ja/aspose.slides/pptxeditexception)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)