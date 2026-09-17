---
title: remove method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
从演示文稿中移除布局。

```python
def remove(self):
    ...
```

### 备注
为避免抛出 PptxEditException，请在此之前检查布局的 HasDependingSlides 属性。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果布局已经从演示文稿中移除，或布局在演示文稿中被使用（其 <br/>            HasDependingSlides 属性为 true），则抛出此异常。 |

### 另请参阅
* 类 [`LayoutSlide`](/slides/python-net/zh/aspose.slides/layoutslide)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)