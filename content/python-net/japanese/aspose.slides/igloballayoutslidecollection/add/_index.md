---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
プレゼンテーションに新しいレイアウト スライドを追加します。

### 戻り値

Added slide.

```python
def add(self, master, layout_type, layout_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide) | 新しいレイアウトのマスタースライド。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype) | 新しいレイアウトのレイアウトタイプ。<br/><br/>Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 新しいレイアウトの名前。渡された名前がすでに使用中の場合は ArgumentException がスローされます。<br/><br/>None パラメータが渡された場合、レイアウトタイプに応じて名前が自動的に生成されます。<br/><br/>(例: "Title Slide" や "1_Title Slide", "2_..", など)。 |

### 備考

1) `layout_type` の値 SlideLayoutType.Custom に対して追加されたレイアウトにはプレースホルダーもシェイプも含まれません。  
2) このメソッドの類似は **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** メソッドで、[`IMasterSlide.layout_slides`](/slides/python-net/ja/aspose.slides/imasterslide/layout_slides) プロパティでアクセスします。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | パラメータ `layout_type` にサポートされていない値が渡された場合にスローされます。現在サポートされていないレイアウトタイプ: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | `master` が None の場合にスローされます。 |
| **RuntimeError(Proxy error(ArgumentException))** | `master` が別のプレゼンテーションに属している場合にスローされます。 |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` の値が `master` のレイアウトコレクションですでに使用中の場合にスローされます。 |

### 参照
* クラス [`IGlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/igloballayoutslidecollection)
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterSlide`](/slides/python-net/ja/aspose.slides/imasterslide)
* 列挙型 [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)