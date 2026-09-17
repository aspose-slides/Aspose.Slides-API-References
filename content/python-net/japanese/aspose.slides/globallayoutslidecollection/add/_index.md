---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
プレゼンテーションに新しいレイアウトスライドを追加します。

### 戻り値

追加されたスライド。

```python
def add(self, master, layout_type, layout_name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide) | 新しいレイアウト用のマスタースライド。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype) | 新しいレイアウトのレイアウトタイプ。<br/><br/>            サポートされているレイアウトタイプ: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 新しいレイアウトの名前。指定された名前が既に使用されている場合は ArgumentException がスローされます。<br/><br/>            None が渡された場合、指定された layout_type に応じて名前が自動的に生成されます（例: "Title Slide"、"1_Title Slide"、"2_.." など）。 |

### 備考

1) `layout_type` の値 SlideLayoutType.Custom の追加レイアウトは、プレースホルダーもシェイプも含まれません。  
2) このメソッドに相当するものは **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** で、[`IMasterSlide.layout_slides`](/slides/python-net/ja/aspose.slides/imasterslide/layout_slides) プロパティでアクセスできます。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | サポートされていない `layout_type` の値が渡された場合にスローされます。現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | `master` が None の場合にスローされます。 |
| **RuntimeError(Proxy error(ArgumentException))** | `master` が別のプレゼンテーションに属している場合にスローされます。 |
| **RuntimeError(Proxy error(ArgumentException))** | `master` のレイアウトコレクションでレイアウト名 `layout_name` が既に使用されている場合にスローされます。 |

### 参照
* クラス [`GlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection)
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide)
* 列挙 [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)