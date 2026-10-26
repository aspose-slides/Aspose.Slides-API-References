---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
将指定的形状移动到形状集合中的新位置。

```python
def reorder(self, index, shape):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 零基目标索引，形状将被放置。 |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 要在集合中移动的 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |

## reorder(self, index, shapes) {#int-listishape}
在形状集合中移动指定的形状，并从给定索引开始放置它们。

```python
def reorder(self, index, shapes):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 零基目标索引，首个指定的形状将被放置；<br/><br/>后续形状将按照提供的顺序依次放置。 |
| shapes | **List[IShape]** | 要在集合中移动的一个或多个 [`IShape`](/slides/python-net/zh/aspose.slides/ishape) 实例。 |

### 参见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)