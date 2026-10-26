---
title: InsertPictureFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 456
url: /es/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) método

Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el marco de imagen. |
| shapeType | [ShapeType](../../shapetype/) | Especifica el tipo de forma contenido en [ShapeType](../../shapetype/), excepto todos los tipos de líneas:

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
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | El [IPPImage](../../ippimage/) para mostrar en el marco de imagen. |

### Valor de retorno

El [IPictureFrame](../../ipictureframe/) recién creado.

## Ver también

* Enumeración [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPictureFrame](../../ipictureframe/)
* Clase [IPPImage](../../ippimage/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)