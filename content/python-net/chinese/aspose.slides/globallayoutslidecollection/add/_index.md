---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
向演示文稿添加新的布局幻灯片。

### 返回

已添加的幻灯片。

```python
def add(self, master, layout_type, layout_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide) | 新布局的母版幻灯片。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype) | 新布局的布局类型。<br/><br/>            支持的布局类型： Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。<br/><br/>            当前不支持的其他布局类型： Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layout_name | **str** | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。<br/><br/>            如果传入 None 参数，则会根据传入的布局类型自动生成名称<br/><br/>            （例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 备注

1) 对于 `layout_type` 为 SlideLayoutType.Custom 的值，添加的布局不包含占位符和形状。  
2) 此方法的对应方法是 **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**，通过 [`IMasterSlide.layout_slides`](/slides/python-net/zh/aspose.slides/imasterslide/layout_slides) 属性访问。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 如果传入了不受支持的 `layout_type` 参数值，则抛出此异常。当前不支持的布局类型： Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 `master` 为 None，则抛出此异常。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果 `master` 属于其他演示文稿，则抛出此异常。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果 `layout_name` 的布局名称已经在 `master` 的布局集合中使用，则抛出此异常。 |

### 另请参阅
* 类 [`GlobalLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/globallayoutslidecollection)
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide)
* 枚举 [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)