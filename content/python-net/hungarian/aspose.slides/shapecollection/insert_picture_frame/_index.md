---
title: insert_picture_frame method
second_title: Aspose.Slides Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Létrehoz egy új képkeretet a megadott képpel, és beszúrja a shape gyűjteménybe a megadott indexen.

### Visszatér

Az újonnan létrehozott [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nulla-alapú index, amelynél a képkeretet be kell illeszteni. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | Megadja a [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ben található alakzat típusát,<br/><br/>            kivéve mindenféle vonalat:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | A képkeret x-koordinátája pontokban. |
| y | **float** | A képkeret y-koordinátája pontokban. |
| width | **float** | A képkeret szélessége pontokban. |
| height | **float** | A képkeret magassága pontokban. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) a képkeretben megjelenítendő. |



### Lásd még
* osztály [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe)
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* enumeráció [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)