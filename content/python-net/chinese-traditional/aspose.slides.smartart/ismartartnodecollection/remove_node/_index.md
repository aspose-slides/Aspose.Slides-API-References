---
title: remove_node method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
依索引移除節點或子節點。

```python
def remove_node(self, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 節點的零基索引 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小於 0。-或- 索引等於或大於同級節點數。 |

## remove_node(self, node_obj) {#ismartartnode}
移除節點或子節點。

```python
def remove_node(self, node_obj):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode) | 要移除的節點。 |

### 參見
* 類別 [`ISmartArtNode`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode)
* 類別 [`ISmartArtNodeCollection`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnodecollection)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 程式庫 [`Aspose.Slides`](/slides/python-net)