---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---


## add_ole_object_frame {#float-float-float-float-ioleembeddeddatainfo}
Creates a new OLE object frame and adds it to the end of the shape collection.

### Returns

The newly created [`IOleObjectFrame`](/slides/python-net/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo) | The information about the embedded OLE data ([`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame {#float-float-float-float-str-str}
Creates a new OLE object frame and adds it to the end of the shape collection.

### Returns

The newly created [`IOleObjectFrame`](/slides/python-net/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new OLE frame, in points. |
| y | **float** | The y-coordinate of the new OLE frame, in points. |
| width | **float** | The width of the new OLE frame, in points. |
| height | **float** | The height of the new OLE frame, in points. |
| class_name | **str** | The class name of the OLE object. |
| path | **str** | The path to the linked file. <br/><br/>This path is stored verbatim in the presentation.<br/><br/>            If a relative path is specified, the file will be inaccessible when opening<br/><br/>            the presentation from a different directory. |



### See Also
* class [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/aspose.slides/ioleobjectframe)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

