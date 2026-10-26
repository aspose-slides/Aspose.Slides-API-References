---
title: insert method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
コレクションの指定位置に新しいレイアウトスライドを挿入します。

### 戻り値

挿入されたスライド。

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| index | **int** | 新しいスライドのインデックス。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype) | 新しいレイアウトのレイアウトタイプ。<br/><br/>サポートされているレイアウトタイプ：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。<br/><br/>現在サポートされていないレイアウトタイプ：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layout_name | **str** | 新しいレイアウトの名前。渡された名前がすでに使用中の場合、ArgumentException がスローされます。<br/><br/>None パラメータが渡された場合、レイアウトタイプに基づいて名前が自動的に生成されます。<br/><br/>（例: "Title Slide" や "1_Title Slide", "2_..", など）。 |

### 備考

`layout_type` の SlideLayoutType.Custom 値用に挿入されたレイアウトにはプレースホルダーもシェイプも含まれていません。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | パラメータ `layout_type` にサポートされていない値が渡された場合にスローされます。現在サポートされていないレイアウトタイプ：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| **RuntimeError(Proxy error(ArgumentException))** | レイアウト名 `layout_name` の値がこのレイアウトコレクションですでに使用されている場合にスローされます。 |

### 参照
* クラス [`ILayoutSlide`](/slides/python-net/ja/aspose.slides/ilayoutslide)
* クラス [`IMasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection)
* 列挙体 [`SlideLayoutType`](/slides/python-net/ja/aspose.slides/slidelayouttype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)