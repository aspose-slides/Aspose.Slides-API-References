---
title: insert_picture_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Maakt een nieuw afbeeldingsframe dat de opgegeven afbeelding bevat en voegt het toe aan de vormverzameling op de opgegeven index.

### Retourwaarde

Het nieuw aangemaakte [`IPictureFrame`](/slides/python-net/nl/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop het afbeeldingsframe moet worden ingevoegd. |
| shape_type | [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype) | Specificeert het vormtype dat zich bevindt in [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype),<br/><br/>            behalve voor alle soorten lijnen:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | De x-coördinaat van het afbeeldingsframe, in punten. |
| y | **float** | De y-coördinaat van het afbeeldingsframe, in punten. |
| width | **float** | De breedte van het afbeeldingsframe, in punten. |
| height | **float** | De hoogte van het afbeeldingsframe, in punten. |
| image | [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) | De [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage) om weer te geven in het afbeeldingsframe. |



### Zie ook
* klasse [`IPictureFrame`](/slides/python-net/nl/aspose.slides/ipictureframe)
* klasse [`IPPImage`](/slides/python-net/nl/aspose.slides/ippimage)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* enumeratie [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)