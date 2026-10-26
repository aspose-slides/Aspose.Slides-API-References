---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides 的 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
创建一个新的摘要缩放框，并将其插入到在指定索引处的形状集合中。

### 返回值

新创建的[`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe)。



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入摘要缩放框的零基索引。 |
| x | **float** | 新摘要缩放框的 x 坐标，以点为单位。 |
| y | **float** | 新摘要缩放框的 y 坐标，以点为单位。 |
| width | **float** | 新摘要缩放框的宽度，以点为单位。 |
| height | **float** | 新摘要缩放框的高度，以点为单位。 |

### 备注

此方法创建一个摘要缩放框，用于汇总演示文稿中所有章节的摘要链接。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 当演示文稿不包含任何章节，或目标幻灯片不属于任何章节时抛出。 |



### 另请参见
* 类 [`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)