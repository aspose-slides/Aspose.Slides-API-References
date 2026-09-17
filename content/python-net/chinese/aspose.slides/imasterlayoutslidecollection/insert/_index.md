---
title: insert method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
在集合的指定位置插入一个新的布局幻灯片。

### 返回

已插入的幻灯片。

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 新幻灯片的索引。 |
| layout_type | [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype) | 用于新布局的布局类型。<br/><br/>支持的布局类型：Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom。<br/><br/>当前不支持的其他布局类型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| layout_name | **str** | 新布局的名称。如果传入的名称已被使用，将抛出 ArgumentException。<br/><br/>如果传入 None 参数，则根据传入的布局类型自动生成名称<br/><br/>（例如 "Title Slide" 或 "1_Title Slide", "2_..", 等）。 |

### 备注

对 `layout_type` 的值 SlideLayoutType.Custom 插入的布局不包含占位符和形状。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 如果传入 `layout_type` 参数的值不受支持，则抛出此异常。当前不受支持的布局类型：Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果布局名称值 `layout_name` 已在此布局集合中使用，则抛出此异常。<br/>            |

### 另请参阅
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`IMasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection)
* 枚举 [`SlideLayoutType`](/slides/python-net/zh/aspose.slides/slidelayouttype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)