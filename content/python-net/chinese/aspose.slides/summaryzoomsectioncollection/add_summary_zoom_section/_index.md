---
title: add_summary_zoom_section method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/summaryzoomsectioncollection/add_summary_zoom_section/
weight: 10
---
## add_summary_zoom_section(self, section) {#isection}
创建新的 Summary Zoom Section 对象并将其添加到集合中

### 返回值

已添加 [`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe) 元素



```python
def add_summary_zoom_section(self, section):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| section | [`ISection`](/slides/python-net/zh/aspose.slides/isection) | 用于新 Summary Zoom Section 元素的章节 [`ISection`](/slides/python-net/zh/aspose.slides/isection) |

### 备注

如果该章节的元素已经存在于集合中，则返回现有元素。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 引用的章节不属于当前演示文稿或不包含任何幻灯片。 |



### 另见
* 类 [`ISection`](/slides/python-net/zh/aspose.slides/isection)
* 类 [`ISummaryZoomFrame`](/slides/python-net/zh/aspose.slides/isummaryzoomframe)
* 类 [`ISummaryZoomSection`](/slides/python-net/zh/aspose.slides/isummaryzoomsection)
* 类 [`SummaryZoomSectionCollection`](/slides/python-net/zh/aspose.slides/summaryzoomsectioncollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)