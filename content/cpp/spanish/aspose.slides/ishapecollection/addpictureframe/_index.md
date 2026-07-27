---
title: AddPictureFrame()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final de la colección de formas.
type: docs
weight: 404
url: /es/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) método


Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Especifica el tipo de forma contenido en [ShapeType](../../shapetype/), excepto para todo tipo de líneas:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | La coordenada x del marco de imagen, en puntos. |
| y | **float** | La coordenada y del marco de imagen, en puntos. |
| width | **float** | El ancho del marco de imagen, en puntos. |
| height | **float** | La altura del marco de imagen, en puntos. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | El [IPPImage](../../ippimage/) que se mostrará en el marco de imagen. |

### Valor devuelto

El [IPictureFrame](../../ipictureframe/) recién creado.

## Ver también

* Enumeración [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPictureFrame](../../ipictureframe/)
* Clase [IPPImage](../../ippimage/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)