---
title: add_picture_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn am Ende der Formensammlung hinzu.

### Returns
Die neu erstellte [`IPictureFrame`](/slides/python-net/de/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) | Gibt den Formtyp an, der in [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype) enthalten ist,<br/><br/> ausgenommen alle Arten von Linien:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Die x-Koordinate des Bildrahmens, in Punkten. |
| y | **float** | Die y-Koordinate des Bildrahmens, in Punkten. |
| width | **float** | Die Breite des Bildrahmens, in Punkten. |
| height | **float** | Die Höhe des Bildrahmens, in Punkten. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) zur Anzeige im Bildrahmen. |



### See Also
* class [`IPictureFrame`](/slides/python-net/de/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* class [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)