---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
删除集合中指定索引处的元素。

```python
def remove_at(self, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要删除的元素的零基索引。 |

### 备注

在检查 master 的 HasDependingSlides 属性之前，以避免抛出 PptxEditException。

### 异常

| 异常 | 描述 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception) | 如果要删除的 master 在演示文稿中被使用（其 HasDependingSlides 属性为 true），则抛出。 |

### 另见
* 类 [`MasterSlideCollection`](/slides/python-net/zh/aspose.slides/masterslidecollection)
* 类 [`PptxEditException`](/slides/python-net/zh/aspose.slides/pptxeditexception)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)