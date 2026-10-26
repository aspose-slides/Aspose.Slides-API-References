---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
將新的版面配置投影片新增至簡報。

### Returns
已新增投影片。

```python
def add(self, master, layout_type, layout_name):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide) | 新版面配置的母片投影片。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype) | 新版面配置的版面類型。<br/><br/>支援的版面類型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。<br/><br/>目前不支援的其他版面類型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layout_name | **str** | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。<br/><br/>如果傳入 None 參數，則會根據傳入的版面類型自動產生名稱 <br/><br/>（例如「Title Slide」或「1_Title Slide」、「2_..」等）。 |

### Remarks
1) 為 `layout_type` 的 SlideLayoutType.Custom 值新增的版面不含任何占位符和形狀。2) 此方法的等價方法是 **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**，可透過 [`IMasterSlide.layout_slides`](/slides/python-net/zh-hant/aspose.slides/imasterslide/layout_slides) 屬性存取。

### Exceptions
| 例外類型 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 如果傳入不支援的 `layout_type` 參數值，將拋出此例外。目前不支援的版面類型包括：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 `master` 為 None，將拋出此例外。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果 `master` 屬於其他簡報，將拋出此例外。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果 `layout_name` 已在 `master` 的版面集合中使用，將拋出此例外。<br/>            collection of the layouts of `master`. |

### See Also
* 類別 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/igloballayoutslidecollection)
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide)
* 列舉 [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)