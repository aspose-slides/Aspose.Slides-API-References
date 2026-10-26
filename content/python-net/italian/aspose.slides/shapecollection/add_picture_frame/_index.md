---
title: add_picture_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Crea un nuovo fotogramma immagine contenente l'immagine specificata e lo aggiunge alla fine della
            collezione di forme.

### Restituisce

Il [`IPictureFrame`](/slides/python-net/it/aspose.slides/ipictureframe) appena creato.

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Specifica il tipo di forma contenuta in [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype),<br/><br/>            eccetto tutti i tipi di linee:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | La coordinata x del fotogramma immagine, in punti. |
| y | **float** | La coordinata y del fotogramma immagine, in punti. |
| width | **float** | La larghezza del fotogramma immagine, in punti. |
| height | **float** | L'altezza del fotogramma immagine, in punti. |
| image | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | Il [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) da visualizzare nel fotogramma immagine. |

### Vedi anche
* classe [`IPictureFrame`](/slides/python-net/it/aspose.slides/ipictureframe)
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* enumerazione [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)