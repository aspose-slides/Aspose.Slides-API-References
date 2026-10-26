---
title: insert_picture_frame method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Vytvoří nový rámeček obrázku obsahující zadaný obraz a vloží jej do kolekce tvarů na zadaném indexu.

### Návratová hodnota
Nově vytvořený [`IPictureFrame`](/slides/python-net/cs/aspose.slides/ipictureframe).

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na kterém se má vložit rámeček obrázku. |
| shape_type | [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype) | Specifikuje typ tvaru obsažený v [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype),<br/><br/>            kromě všech druhů čar:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | x-souřadnice rámečku obrázku v bodech. |
| y | **float** | y-souřadnice rámečku obrázku v bodech. |
| width | **float** | Šířka rámečku obrázku v bodech. |
| height | **float** | Výška rámečku obrázku v bodech. |
| image | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) k zobrazení v rámečku obrázku. |

### Viz také
* třída [`IPictureFrame`](/slides/python-net/cs/aspose.slides/ipictureframe)
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* enumerace [`ShapeType`](/slides/python-net/cs/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)