---
title: add_picture_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`IPictureFrame`](/slides/python-net/sv/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype) | Anger formtypen som finns i [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype),<br/><br/>            förutom alla typer av linjer:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | X-koordinaten för bildramen, i punkter. |
| y | **float** | Y-koordinaten för bildramen, i punkter. |
| width | **float** | Bredden på bildramen, i punkter. |
| height | **float** | Höjden på bildramen, i punkter. |
| image | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Den [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) som ska visas i bildramen. |



### Se även
* klass [`IPictureFrame`](/slides/python-net/sv/aspose.slides/ipictureframe)
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)