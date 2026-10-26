---
title: add_picture_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Maakt een nieuw afbeeldingframe dat de opgegeven afbeelding bevat en voegt deze toe aan het einde van de shape-collectie.

### Retourwaarde

Het nieuw aangemaakte [`IPictureFrame`](/slides/python-net/nl/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | Specificeert het shape-type dat zich bevindt in [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype),<br/><br/>            behalve alle soorten lijnen:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | De x-coördinaat van het afbeeldingframe, in punten. |
| y | **float** | De y-coördinaat van het afbeeldingframe, in punten. |
| width | **float** | De breedte van het afbeeldingframe, in punten. |
| height | **float** | De hoogte van het afbeeldingframe, in punten. |
| image | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | De [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) die moet worden weergegeven in het afbeeldingframe. |



### Zie ook
* class [`IPictureFrame`](/slides/python-net/nl/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* class [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)