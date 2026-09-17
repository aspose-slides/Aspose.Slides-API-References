---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/reorder/
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
| index | **int** | 形状将被放置的零基目标索引。 |
| shape | [`IShape`](/slides/python-net/zh/aspose.slides/ishape) | 集合中要移动的[`IShape`](/slides/python-net/zh/aspose.slides/ishape)。 |

## reorder(self, index, shapes) {#int-listishape}
将指定的形状在形状集合中移动，从给定索引开始放置它们。

```python
def reorder(self, index, shapes):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 第一个指定形状将被放置的零基目标索引；<br/><br/>随后形状按照提供的顺序依次放置。 |
| shapes | **List[IShape]** | 集合中要移动的一个或多个[`IShape`](/slides/python-net/zh/aspose.slides/ishape)实例。 |

### 另见
* 类 [`IShape`](/slides/python-net/zh/aspose.slides/ishape)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)