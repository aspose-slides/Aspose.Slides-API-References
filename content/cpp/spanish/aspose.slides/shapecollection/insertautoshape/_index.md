---
title: InsertAutoShape()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato de plantilla predeterminado.
type: docs
weight: 378
url: /es/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) método

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato de plantilla predeterminado.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la nueva forma automática. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma automática a insertar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |

### Valor devuelto

El [IAutoShape](../../iautoshape/) recién creado.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) método

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo de plantilla predeterminado.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la forma automática. |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma automática a insertar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |
| createFromTemplate | **bool** | Verdadero para aplicar el estilo de plantilla predeterminado (incluyendo un nombre no vacío, estilo sencillo y texto centrado); falso para crear la forma con todas las propiedades establecidas a sus valores predeterminados. |

### Valor devuelto

El [IAutoShape](../../iautoshape/) recién creado.

## Ver también

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)