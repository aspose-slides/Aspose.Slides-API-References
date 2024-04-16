---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---


## insert_ole_object_frame {#int-float-float-float-float-ioleembeddeddatainfo}
Creates a new OLE object and inserts it to a collection at the specified index.

### Returns

Created OLE object.



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which OLE object should be inserted. |
| x | **float** | X coordinate of a new OLE frame. |
| y | **float** | Y coordinate of a new OLE frame. |
| width | **float** | Width of a new OLE frame. |
| height | **float** | Height of a new OLE frame. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo) | Embedded data info [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo). |


## insert_ole_object_frame {#int-float-float-float-float-str-str}
Creates a new OLE object and inserts it to a collection at the specified index.

### Returns

Created OLE object.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which OLE object should be inserted. |
| x | **float** | X coordinate of a new OLE frame. |
| y | **float** | Y coordinate of a new OLE frame. |
| width | **float** | Width of a new OLE frame. |
| height | **float** | Height of a new OLE frame. |
| class_name | **str** | Name of an OLE class. |
| path | **str** | Path to the linked file. |



### See Also
* class [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/aspose.slides/ioleobjectframe)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

