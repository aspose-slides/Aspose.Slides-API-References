---
title: add_picture_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Crea un nuovo riquadro immagine contenente l'immagine specificata e lo aggiunge alla fine della raccolta di forme.

### Ritorna

Il nuovo [`IPictureFrame`](/slides/python-net/it/aspose.slides/ipictureframe) creato.



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Specificare il tipo di forma contenuto in [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype),<br/><br/>            eccetto tutti i tipi di linee:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | La coordinata x del riquadro immagine, in punti. |
| y | **float** | La coordinata y del riquadro immagine, in punti. |
| width | **float** | La larghezza del riquadro immagine, in punti. |
| height | **float** | L'altezza del riquadro immagine, in punti. |
| image | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | Il [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) da visualizzare nel riquadro immagine. |



### Vedi anche
* classe [`IPictureFrame`](/slides/python-net/it/aspose.slides/ipictureframe)
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* enumerazione [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)