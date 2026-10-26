---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
コレクションの末尾に新しいレイアウトスライドを追加します。

### 戻り値

追加されたスライド。

```python
def add(self, layout_type, layout_name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype) | 新しいレイアウトのレイアウトタイプです。<br/><br/>            サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 新しいレイアウトの名前です。指定された名前がすでに使用されている場合、ArgumentException がスローされます。<br/><br/>            None パラメーターが渡された場合、渡された layout_type に基づいて名前が自動的に生成されます。<br/><br/>            （例: "Title Slide" や "1_Title Slide", "2_..", など）。 |

### 備考

1) `layout_type` が `SlideLayoutType.Custom` の値の場合、追加されるレイアウトにはプレースホルダーもシェイプも含まれません。  
2) このメソッドに相当するものは、[`IPresentation.layout_slides`](/slides/python-net/ja/aspose.slides/ipresentation/layout_slides) プロパティでアクセスできる **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** メソッドです。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | `layout_type` パラメーターにサポートされていない値が渡された場合にスローされます。現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` の値がこのレイアウトコレクションですでに使用されている場合にスローされます。 |

### 関連項目
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`MasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection)
* 列挙型 [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)