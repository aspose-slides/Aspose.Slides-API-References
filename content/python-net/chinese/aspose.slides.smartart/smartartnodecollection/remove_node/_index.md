---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
按索引删除节点或子节点

```python
def remove_node(self, index):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 节点的零基索引 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小于 0。或 索引等于或大于兄弟节点的计数 |

## remove_node(self, node) {#ismartartnode}
删除节点或子节点

```python
def remove_node(self, node):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode) | 要删除的节点 |

### 另见
* 类 [`ISmartArtNode`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode)
* 类 [`SmartArtNodeCollection`](/slides/python-net/zh/aspose.slides.smartart/smartartnodecollection)
* 模块 [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)