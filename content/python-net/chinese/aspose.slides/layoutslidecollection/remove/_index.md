---
title: remove method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
从集合中移除布局。


```python
def remove(self, value):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 要从集合中移除的布局幻灯片。 |

### 备注

1) 为避免抛出 PptxEditException，请在此之前检查布局的 HasDependingSlides 属性。  
2) 您也可以使用 [`ILayoutSlide.remove`](/slides/python-net/zh/aspose.slides/ilayoutslide/remove) 方法来简化代码。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果布局在演示文稿中已被使用（其 HasDependingSlides 属性为 true），则抛出此异常。 |



### 另请参见
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`LayoutSlideCollection`](/slides/python-net/zh/aspose.slides/layoutslidecollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)