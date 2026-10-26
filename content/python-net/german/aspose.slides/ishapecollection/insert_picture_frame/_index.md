---
title: insert_picture_frame method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn in die Form-Sammlung an der angegebenen Position ein.

### Rückgabewert

Das neu erstellte [`IPictureFrame`](/slides/python-net/de/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Bildrahmen eingefügt werden soll. |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Gibt den Formtyp an, der in [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) enthalten ist,<br/><br/>            mit Ausnahme aller Linienarten:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Die x-Koordinate des Bildrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Bildrahmens in Punkten. |
| width | **float** | Die Breite des Bildrahmens in Punkten. |
| height | **float** | Die Höhe des Bildrahmens in Punkten. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) das im Bildrahmen angezeigt wird. |



### Siehe auch
* Klasse [`IPictureFrame`](/slides/python-net/de/aspose.slides/ipictureframe)
* Klasse [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Aufzählung [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)