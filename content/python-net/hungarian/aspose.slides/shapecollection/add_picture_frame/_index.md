---
title: add_picture_frame method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Létrehoz egy új képkockát, amely a megadott képet tartalmazza, és hozzáadja a formagyűjtemény végéhez.

### Visszatérési érték

Az újonnan létrehozott [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe).

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | Megadja a [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ben szereplő alakzat típusát,<br/><br/>            kivéve mindenféle vonalak:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | A képkocka x-koordinátája pontban. |
| y | **float** | A képkocka y-koordinátája pontban. |
| width | **float** | A képkocka szélessége pontban. |
| height | **float** | A képkocka magassága pontban. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) a képkockában megjelenítésre. |

### Lásd még
* osztály [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe)
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* enumeráció [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)