---
title: insert_picture_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Skapar en ny bildram som innehåller den angivna bilden och infogar den i shape-samlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`IPictureFrame`](/slides/python-net/sv/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade index där bildramen ska infogas. |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Anger shape-typen som finns i [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype),<br/><br/>            förutom alla sorters linjer:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | x-koordinaten för bildramen, i punkter. |
| y | **float** | y-koordinaten för bildramen, i punkter. |
| width | **float** | Bredden på bildramen, i punkter. |
| height | **float** | Höjden på bildramen, i punkter. |
| image | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) som ska visas i bildramen. |



### Se även
* class [`IPictureFrame`](/slides/python-net/sv/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* class [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)