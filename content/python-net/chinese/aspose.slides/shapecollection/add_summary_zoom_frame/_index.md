---
title: add_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
创建一个新的 Summary Zoom 框架并将其添加到 shape collection 的末尾。

### 返回

新创建的 [`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe)。

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新的 Summary Zoom 框架的 x 坐标（单位为点）。 |
| y | **float** | 新的 Summary Zoom 框架的 y 坐标（单位为点）。 |
| width | **float** | 新的 Summary Zoom 框架的宽度（单位为点）。 |
| height | **float** | 新的 Summary Zoom 框架的高度（单位为点）。 |

### 备注

此方法创建一个新的 Summary Zoom 并将对象集合放入其中，以适用于此演示文稿中的所有章节。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果演示文稿中没有章节，或目标幻灯片不属于任何章节，则抛出此异常。 |

### 另请参见
* 类 [`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)