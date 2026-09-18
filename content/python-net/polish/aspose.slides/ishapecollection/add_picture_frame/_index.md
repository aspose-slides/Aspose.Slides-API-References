---
title: add_picture_frame method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Tworzy nową ramkę obrazu zawierającą określony obraz i dodaje ją na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`IPictureFrame`](/slides/python-net/pl/aspose.slides/ipictureframe).

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype) | Określa typ kształtu zawarty w [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype),<br/><br/>            z wyjątkiem wszystkich rodzajów linii:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Współrzędna x ramki obrazu, w punktach. |
| y | **float** | Współrzędna y ramki obrazu, w punktach. |
| width | **float** | Szerokość ramki obrazu, w punktach. |
| height | **float** | Wysokość ramki obrazu, w punktach. |
| image | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) do wyświetlenia w ramce obrazu. |

### Zobacz także
* klasa [`IPictureFrame`](/slides/python-net/pl/aspose.slides/ipictureframe)
* klasa [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* enumeracja [`ShapeType`](/slides/python-net/pl/aspose.slides/shapetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)