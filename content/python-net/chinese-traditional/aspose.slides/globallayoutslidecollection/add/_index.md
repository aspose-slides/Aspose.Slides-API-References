---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
將新的版面投影片新增至簡報中。

### 返回值

已新增的投影片。

```python
def add(self, master, layout_type, layout_name):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide) | 新版面的母投影片。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype) | 新版面的版面類型。<br/><br/>            支援的版面類型：Title、TitleOnly、Blank、TitleAndObject、VerticalText、VerticalTitleAndText、TwoObjects、SectionHeader、TwoTextAndTwoObjects、TitleObjectAndCaption、PictureAndCaption、Custom。<br/><br/>            目前不支援的其他版面類型：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| layout_name | **str** | 新版面的名稱。若傳入的名稱已被使用，將拋出 ArgumentException。<br/><br/>            若傳入 None，則會根據傳入的版面類型自動產生名稱<br/><br/>            （例如「Title Slide」或「1_Title Slide」、「2_…」等）。 |

### 備註

1) 針對 `layout_type` 為 SlideLayoutType.Custom 的值所新增的版面不包含任何佔位符與圖形。  
2) 此方法的對應方法是 **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**，可透過 [`IMasterSlide.layout_slides`](/slides/python-net/zh-hant/aspose.slides/imasterslide/layout_slides) 屬性存取。

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 當傳入不支援的 `layout_type` 參數值時拋出。現在不支援的版面類型：Text、TwoColumnText、Table、TextAndChart、ChartAndText、Diagram、Chart、TextAndClipArt、ClipArtAndText、TextAndObject、ObjectAndText、Object、TextAndMedia、MediaAndText、ObjectOverText、TextOverObject、TextAndTwoObjects、TwoObjectsAndText、TwoObjectsOverText、FourObjects、ClipArtAndVerticalText、VerticalTitleAndTextOverChart、ObjectAndTwoObject、TwoObjectsAndObject。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 `master` 為 None 時拋出。 |
| **RuntimeError(Proxy error(ArgumentException))** | 當 `master` 屬於其他簡報時拋出。 |
| **RuntimeError(Proxy error(ArgumentException))** | 當 `layout_name` 已在 `master` 的版面集合中使用時拋出。 |

### 另見
* 類別 [`GlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection)
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide)
* 列舉 [`SlideLayoutType`](/slides/python-net/zh-hant/aspose.slides/slidelayouttype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)