---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
通过索引删除节点或子节点。


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小于 0。 -或- 索引等于或大于兄弟节点计数。 |


## remove_node(self, node_obj) {#ismartartnode}
删除节点或子节点。


```python
def remove_node(self, node_obj):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode) | 要删除的节点。 |



### 另请参见
* 类 [`ISmartArtNode`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode)
* 类 [`ISmartArtNodeCollection`](/slides/python-net/zh/aspose.slides.smartart/ismartartnodecollection)
* 模块 [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* 库 [`Aspose.Slides`](/slides/python-net)