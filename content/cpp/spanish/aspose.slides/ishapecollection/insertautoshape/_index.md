---
title: InsertAutoShape()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato predeterminado de la plantilla.
type: docs
weight: 339
url: /es/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) método

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato predeterminado de la plantilla.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se insertará la nueva forma automática. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma automática que se insertará. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |

### Valor devuelto

La [IAutoShape](../../iautoshape/) recién creada.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) método

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo predeterminado de la plantilla.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se insertará la forma automática. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma automática que se insertará. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |
| createFromTemplate | **bool** | Verdadero para aplicar el estilo predeterminado de la plantilla (incluyendo un nombre no vacío, estilo simple y texto centrado); falso para crear la forma con todas sus propiedades establecidas a sus valores predeterminados. |

### Valor devuelto

La [IAutoShape](../../iautoshape/) recién creada.

## Ver también

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)