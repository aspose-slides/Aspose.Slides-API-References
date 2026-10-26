---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imasterlayoutslidecollection/add/
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

| Parameter | Type | Description |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype) | 新しいレイアウトのレイアウトタイプ。<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 新しいレイアウトの名前。すでに使用中の名前が渡された場合は ArgumentException がスローされます。<br/><br/>            None パラメーターが渡された場合、渡されたレイアウトタイプに応じて自動的に名前が生成されます (例: "Title Slide" や "1_Title Slide", "2_..", など)。 |

### 備考

1) `layout_type` の SlideLayoutType.Custom の値に対して追加されたレイアウトは、プレースホルダーもシェイプも含まれていません。  
2) このメソッドの類似は **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** にアクセスでき、[`IPresentation.layout_slides`](/slides/python-net/ja/aspose.slides/ipresentation/layout_slides) プロパティで使用されます。

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | `layout_type` パラメーターにサポートされていない値が渡された場合にスローされます。現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | このコレクション内ですでに使用中の `layout_name` が指定された場合にスローされます。 |

### 関連項目
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection)
* 列挙 [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)