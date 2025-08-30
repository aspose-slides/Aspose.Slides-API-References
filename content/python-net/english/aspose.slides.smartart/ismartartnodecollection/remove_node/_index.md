---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---


## remove_node {#int}
Remove node or sub node by index.


```python
def remove_node(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Zero-based index of node |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index is less than 0.  -or- index is equal to or greater than siblings count. |


## remove_node {#asposeslidessmartartismartartnode}
Remove node or sub node.


```python
def remove_node(self, node_obj):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/aspose.slides.smartart/ismartartnode) | Node to remove. |



### See Also
* class [`ISmartArtNode`](/slides/python-net/aspose.slides.smartart/ismartartnode)
* class [`ISmartArtNodeCollection`](/slides/python-net/aspose.slides.smartart/ismartartnodecollection)
* module [`aspose.slides.smartart`](/slides/python-net/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)

