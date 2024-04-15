---
title: insert_picture_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---


## insert_picture_frame {#int-shapetype-float-float-float-float-ippimage}
Creates a new PictureFrame and inserts it to the collection at the specified index.

### Returns

Created PictureFrame object.



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based index at which value should be inserted. |
| shape_type | ShapeType | The shape contained in the set [`ShapeType`](/slides/python-net/aspose.slides/shapetype)<br/><br/>            of shapes, except all sorts of lines:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| image | IPPImage | The image of picture frame. |



### See Also
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
