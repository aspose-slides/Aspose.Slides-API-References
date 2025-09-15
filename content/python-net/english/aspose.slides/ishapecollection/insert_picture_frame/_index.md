---
title: insert_picture_frame method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---


## insert_picture_frame {#int-shapetype-float-float-float-float-ippimage}
Creates a new picture frame containing the specified image and inserts it into the shape
            collection at the specified index.

### Returns

The newly created [`IPictureFrame`](/slides/python-net/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the picture frame. |
| shape_type | [`ShapeType`](/slides/python-net/aspose.slides/shapetype) | Specifies the shape type contained in [`ShapeType`](/slides/python-net/aspose.slides/shapetype),<br/><br/>            except for all kinds of lines:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | The x-coordinate of the picture frame, in points. |
| y | **float** | The y-coordinate of the picture frame, in points. |
| width | **float** | The width of the picture frame, in points. |
| height | **float** | The height of the picture frame, in points. |
| image | [`IPPImage`](/slides/python-net/aspose.slides/ippimage) | The [`IPPImage`](/slides/python-net/aspose.slides/ippimage) to display in the picture frame. |



### See Also
* class [`IPictureFrame`](/slides/python-net/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/aspose.slides/ippimage)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

