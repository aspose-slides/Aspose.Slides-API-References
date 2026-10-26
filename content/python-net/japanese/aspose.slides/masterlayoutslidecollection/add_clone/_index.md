---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。

### 戻り値

追加されたスライド。

```python
def add_clone(self, source_layout):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | クローン対象のスライド。 |

### 補足

1) 新しいレイアウトは、このレイアウトスライドコレクションの親マスタースライドにリンクされます。したがって、PowerPoint の「目的のテーマを使用」オプションを使用したコピー/貼り付けと同等です。  
2) このメソッドに相当するものは、**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** メソッドで、[`IPresentation.layout_slides`](/slides/python-net/ja/aspose.slides/ipresentation/layout_slides) プロパティでアクセスします。

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`MasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)