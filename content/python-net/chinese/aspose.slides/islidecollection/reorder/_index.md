---
title: reorder method
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islidecollection/reorder/
weight: 110
---
## reorder(self, index, slide) {#int-islide}
将幻灯片从集合中移动到指定位置。

```python
def reorder(self, index, slide):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 目标索引。 |
| slide | [`ISlide`](/slides/python-net/zh/aspose.slides/islide) | 要移动的幻灯片。 |

## reorder(self, index, slides) {#int-listislide}
将幻灯片从集合中移动到指定位置。幻灯片将从 index 开始按它们在列表中出现的顺序放置。

```python
def reorder(self, index, slides):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 目标索引。 |
| slides | **List[ISlide]** | 要移动的幻灯片。 |

### 另见
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`ISlideCollection`](/slides/python-net/zh/aspose.slides/islidecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)