---
title: insert method
second_title: Aspose.Slides 用於 Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
在集合的指定位置插入新的版面配置投影片。

### 回傳

已插入的投影片。

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 新投影片的索引。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype) | 新版面的版面配置類型。<br/><br/>            支援的版面配置類型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。<br/><br/>            目前不支援的其他版面配置類型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layout_name | **str** | 新版面的名稱。如果傳入的名稱已被使用，將拋出 ArgumentException。<br/><br/>            如果傳入 None 參數，則會根據傳入的版面配置類型自動產生名稱 <br/><br/>            （例如「Title Slide」或「1_Title Slide」、「2_..」等）。 |

### 備註

插入的版面配置為 `layout_type` 的 SlideLayoutType.Custom 值，且不包含任何占位符和圖形。

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 如果傳入不受支援的 `layout_type` 參數值，將拋出此例外。目前不支援的版面配置類型有：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果版面名稱 `layout_name` 的值已在此版面集合中使用，將拋出此例外。<br/>            |

### 參考
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`MasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection)
* 列舉 [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)