---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---


## add_ole_object_frame {#float-float-float-float-ioleembeddeddatainfo}
Adds a new OLE object to the end of a collection.

### Returns

Created OLE object.



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| data_info | IOleEmbeddedDataInfo | Embedded data info [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo). |



## add_ole_object_frame {#float-float-float-float-string-string}
Adds a new OLE object to the end of a collection.

### Returns

Created OLE object.



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | X coordinate of a new OLE frame. |
| y | float | Y coordinate of a new OLE frame. |
| width | float | Width of a new OLE frame. |
| height | float | Height of a new OLE frame. |
| class_name | string | Name of an OLE class. |
| path | string | Path to the linked file.<br/><br/>The path is stored in the presentation as is. If a relative path is specified <br/><br/>            the corresponding file will be inaccessible when opening the presentation from a different directory. |



