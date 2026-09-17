---
title: insert_picture_frame method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IPictureFrame`](/slides/python-net/es/aspose.slides/ipictureframe) recién creado.



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que insertar el marco de imagen. |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | Especifica el tipo de forma contenido en [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype),<br/><br/>            excepto todos los tipos de líneas:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | La coordenada x del marco de imagen, en puntos. |
| y | **float** | La coordenada y del marco de imagen, en puntos. |
| width | **float** | El ancho del marco de imagen, en puntos. |
| height | **float** | La altura del marco de imagen, en puntos. |
| image | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | El [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) para mostrar en el marco de imagen. |



### Ver también
* clase [`IPictureFrame`](/slides/python-net/es/aspose.slides/ipictureframe)
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* enumeración [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)