---
title: add_picture_frame method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IPictureFrame`](/slides/python-net/cs/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | Určuje typ tvaru obsažený v [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype),<br/><br/>vyjma všech druhů čar:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | X-souřadnice rámečku obrázku v bodech. |
| y | **float** | Y-souřadnice rámečku obrázku v bodech. |
| width | **float** | Šířka rámečku obrázku v bodech. |
| height | **float** | Výška rámečku obrázku v bodech. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) k zobrazení v rámečku obrázku. |



### Viz také
* třída [`IPictureFrame`](/slides/python-net/cs/aspose.slides/ipictureframe)
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* výčet [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)