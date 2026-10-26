---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
移除集合中指定索引处的元素。

```python
def remove_at(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 要移除的元素的零基索引。 |

### 备注

1) 为避免抛出 PptxEditException，请在之前检查 layout 的 HasDependingSlides 属性。  
2) 您也可以使用 [`ILayoutSlide.remove`](/slides/python-net/zh/aspose.slides/ilayoutslide/remove) 方法来简化代码。

### 异常

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果布局在演示文稿中被使用（其 HasDependingSlides 属性为 true），则抛出此异常。 |

### 另请参见
* 类 [`MasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/masterlayoutslidecollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)