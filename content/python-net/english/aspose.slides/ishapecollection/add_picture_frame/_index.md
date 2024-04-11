---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_picture_frame/
weight: 330
---


## add_picture_frame {#ShapeType-float-float-float-float-IPPImage}
Creates a new PictureFrame and adds it to the end of the collection.

### Returns

Created PictureFrame object.



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | ShapeType | The shape contained in the set [`ShapeType`](/slides/python-net/aspose.slides/shapetype)<br/><br/>            of shapes, except all sorts of lines:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |
| image | IPPImage | The image of picture frame. |



