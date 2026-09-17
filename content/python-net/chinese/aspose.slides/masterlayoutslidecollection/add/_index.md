---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
在集合末尾添加一个新的布局幻灯片。

### 返回

已添加的幻灯片。

```python
def add(self, layout_type, layout_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype) | 新布局的布局类型。<br/><br/>            支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。<br/><br/>            目前不支持的其他布局类型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layout_name | **str** | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。<br/><br/>            如果传入 None 参数，则会根据传入的布局类型自动生成名称<br/><br/>            （例如 “Title Slide” 或 “1_Title Slide”, “2_..” 等）。 |

### 备注

1) `layout_type` 为 SlideLayoutType.Custom 的添加布局不包含占位符和形状。  
2) 此方法的等价形式是通过 [`IPresentation.layout_slides`](/slides/python-net/zh/aspose.slides/ipresentation/layout_slides) 属性访问的 **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** 方法。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 当传入不受支持的 `layout_type` 参数值时抛出。当前不支持的布局类型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| **RuntimeError(Proxy error(ArgumentException))** | 当布局名称 `layout_name` 已在此布局集合中使用时抛出。 |

### 另请参见
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`MasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection)
* 枚举 [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)