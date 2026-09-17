---
title: remove_at method
second_title: Aspose.Slides 适用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Removes the element at the specified index of the collection.

```python
def remove_at(self, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要删除的元素的零基索引。 |

### 备注

1) 为避免抛出 PptxEditException，请在此之前检查 layout 的 HasDependingSlides 属性。
2) 也可以使用 [`ILayoutSlide.remove`](/slides/python-net/zh/aspose.slides/ilayoutslide/remove) 方法来简化代码。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果 layout 已在演示文稿中使用（其 HasDependingSlides 属性为 true），则抛出此异常。 |

### 另见
* 类 [`IMasterLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/imasterlayoutslidecollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)