---
title: add_picture_frame method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Új képkeretet hoz létre a megadott képpel, és hozzáadja a alakzatgyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | Megadja a [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ban lévő alakzat típusát, kivéve mindenféle vonalat:<br/><br/>            ShapeType.Line,<br/><br/>            ShapeType.StraightConnector1,<br/><br/>            ShapeType.BentConnector2,<br/><br/>            ShapeType.BentConnector3,<br/><br/>            ShapeType.BentConnector4,<br/><br/>            ShapeType.BentConnector5,<br/><br/>            ShapeType.CurvedConnector2,<br/><br/>            ShapeType.CurvedConnector3,<br/><br/>            ShapeType.CurvedConnector4,<br/><br/>            ShapeType.CurvedConnector5. |
| x | **float** | A képkeret x-koordinátája pontban. |
| y | **float** | A képkeret y-koordinátája pontban. |
| width | **float** | A képkeret szélessége pontban. |
| height | **float** | A képkeret magassága pontban. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) a képkeretben megjelenítendő. |



### Lásd még
* osztály [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe)
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* enumeráció [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)