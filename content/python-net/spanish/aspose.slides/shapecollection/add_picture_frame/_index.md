---
title: add_picture_frame method
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Crea un nuevo marco de imagen que contiene la imagen especificada y lo añade al final de la colección de formas.

### Devuelve

El [`IPictureFrame`](/slides/python-net/es/aspose.slides/ipictureframe) recién creado.



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | Especifica el tipo de forma contenido en [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype),<br/><br/>            excepto para todo tipo de líneas:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | La coordenada x del marco de imagen, en puntos. |
| y | **float** | La coordenada y del marco de imagen, en puntos. |
| width | **float** | El ancho del marco de imagen, en puntos. |
| height | **float** | La altura del marco de imagen, en puntos. |
| image | [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) | El [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage) para mostrar en el marco de imagen. |



### Ver también
* clase [`IPictureFrame`](/slides/python-net/es/aspose.slides/ipictureframe)
* clase [`IPPImage`](/slides/python-net/es/aspose.slides/ippimage)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* enumeración [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)