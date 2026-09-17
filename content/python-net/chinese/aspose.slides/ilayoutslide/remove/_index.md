---
title: remove method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
从演示文稿中移除布局。

```python
def remove(self):
    ...
```

### 备注

为了避免抛出 PptxEditException，请在之前检查 layout 的 HasDependingSlides 属性。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果布局已经从演示文稿中移除，或布局在演示文稿中被使用（其 <br/>            HasDependingSlides 属性为 true）。 |

### 另请参见
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)