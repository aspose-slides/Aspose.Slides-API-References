---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imasterlayoutslidecollection/add_clone/
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

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide) | クローン対象のスライド。 |

### 備考

1) 新しいレイアウトは、このレイアウトスライドコレクションの親マスタースライドにリンクされます。  
   したがって、これは PowerPoint の "Use Destination Theme" オプションを使用したコピー/貼り付けに相当します。  
2) このメソッドに相当するものは、**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** メソッドで、[`IPresentation.layout_slides`](/slides/python-net/ja/aspose.slides/ipresentation/layout_slides) プロパティでアクセスします。

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)