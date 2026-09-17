---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
创建一个新的 Summary Zoom frame 并将其插入到指定索引处的 shape 集合中。

### 返回

新创建的 [`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe)。

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 用于插入 Summary Zoom frame 的零基索引。 |
| x | **float** | 新 Summary Zoom frame 的 x 坐标，单位为点。 |
| y | **float** | 新 Summary Zoom frame 的 y 坐标，单位为点。 |
| width | **float** | 新 Summary Zoom frame 的宽度，单位为点。 |
| height | **float** | 新 Summary Zoom frame 的高度，单位为点。 |

### 备注

此方法创建一个 Summary Zoom frame，用于聚合演示文稿中所有章节的摘要链接。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果演示文稿不包含任何章节，或目标幻灯片不属于任何章节，则抛出此异常。 |

### 另请参见
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 类 [`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)