---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
在集合的末端新增一個版面投影片。

### 回傳
已新增的投影片。

```python
def add(self, layout_type, layout_name):
    ...
```

| 參數 | 類型 |說明 |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype) | 新版面的版面類型。<br/><br/>            支援的版面類型： Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            目前不支援的其他版面類型： Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 新版面的名稱。如果傳入的名稱已被使用，將拋出 ArgumentException。<br/><br/>            如果傳入 None 參數，則會根據傳入的版面類型自動產生名稱 <br/><br/>            （例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 備註
1) 為 `layout_type` 的值 SlideLayoutType.Custom 所新增的版面不包含任何佔位符與圖形。  
2) 此方法的對應是 **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**，可透過 [`IPresentation.layout_slides`](/slides/python-net/zh-hant/aspose.slides/ipresentation/layout_slides) 屬性存取。

### 例外
| 例外 |說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 如果傳入不支援的 `layout_type` 參數值，將拋出。 Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | 如果版面名稱值 `layout_name` 已在此版面集合中被使用，將拋出。<br/>            此集合中的版面。 |

### 另見
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`MasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection)
* 列舉 [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)