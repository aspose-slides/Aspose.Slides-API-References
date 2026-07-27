---
title: AddAutoShape()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una nueva auto shape con formato predeterminado y la agrega al final de la colección de shapes.
type: docs
weight: 313
url: /es/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method

Crea una nueva auto shape con formato predeterminado y la agrega al final de la colección de shapes.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la auto shape a añadir. |
| x | **float** | La coordenada x del marco de la shape, en puntos. |
| y | **float** | La coordenada y del marco de la shape, en puntos. |
| width | **float** | El ancho del marco de la shape, en puntos. |
| height | **float** | La altura del marco de la shape, en puntos. |

### Valor devuelto

La [IAutoShape](../../iautoshape/) recién creada.

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method

Crea una nueva auto shape y la agrega al final de la colección de shapes, opcionalmente inicializándola con el formato de plantilla predeterminado.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la auto shape a añadir. |
| x | **float** | La coordenada x del marco de la shape, en puntos. |
| y | **float** | La coordenada y del marco de la shape, en puntos. |
| width | **float** | El ancho del marco de la shape, en puntos. |
| height | **float** | La altura del marco de la shape, en puntos. |
| createFromTemplate | **bool** | True para aplicar el estilo de plantilla predeterminado (estilo simple, texto centrado y nombre no vacío) a la nueva shape; false para crear la shape con todas las propiedades establecidas a sus valores predeterminados. |

### Valor devuelto

La [IAutoShape](../../iautoshape/) recién creada.

## Ver también

* Enumeración [ShapeType](../../shapetype/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)