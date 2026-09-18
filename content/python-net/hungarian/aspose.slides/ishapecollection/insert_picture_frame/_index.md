---
title: insert_picture_frame method
second_title: Aspose.Slides Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Létrehoz egy új képkeretet, amely a megadott képet tartalmazza, és beilleszti a forma gyűjteménybe a megadott indexnél.

### Returns
Az újonnan létrehozott [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe).

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nulla alapú index, amelynél be kell illeszteni a képkeretet. |
| shape_type | [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype) | Megadja a [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)-ben található alakzat típusát, kivéve mindenféle vonalat:<br/><br/>            <br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | A képkeret x-koordinátája, pontban. |
| y | **float** | A képkeret y-koordinátája, pontban. |
| width | **float** | A képkeret szélessége, pontban. |
| height | **float** | A képkeret magassága, pontban. |
| image | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | A [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage), amely a képkeretben megjelenik. |

### Lásd még
* osztály [`IPictureFrame`](/slides/python-net/hu/aspose.slides/ipictureframe)
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* felsorolás [`ShapeType`](/slides/python-net/hu/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)