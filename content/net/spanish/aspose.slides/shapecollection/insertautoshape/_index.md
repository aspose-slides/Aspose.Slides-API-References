---
title: InsertAutoShape
second_title: Aspose.Sildes para .NET Reference de la API
description: Crea un nuevo AutoShape, lo ajusta desde la plantilla predeterminada e inserta en la colección en el índice especificado. Nota el tipo de la forma será determinado por el parámetro shapeType.
type: docs
weight: 300
url: /es/aspose.slides/shapecollection/insertautoshape/
---

## InsertAutoShape(int, ShapeType, float, float, float, float) {#insertautoshape}

Crea un nuevo AutoShape, lo ajusta desde la plantilla predeterminada e inserta en la colección en el índice especificado. Nota: el tipo de la forma será determinado por el parámetro shapeType.

```csharp
public IAutoShape InsertAutoShape(int index, ShapeType shapeType, float x, float y, float width, 
    float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el valor. |
| shapeType | ShapeType | Un [`ShapeType`](../../shapetype) de forma. |
| x | Single | La coordenada X para el lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para el lado superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |

### Valor de Retorno

Objeto AutoShape creado.

### Véase También

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertAutoShape(int, ShapeType, float, float, float, float, bool) {#insertautoshape_1}

Crea un nuevo AutoShape e inserta en la colección en el índice especificado. Nota: el tipo de la forma será determinado por el parámetro shapeType.

```csharp
public IAutoShape InsertAutoShape(int index, ShapeType shapeType, float x, float y, float width, 
    float height, bool createFromTemplate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el valor. |
| shapeType | ShapeType | Un [`ShapeType`](../../shapetype) de forma. |
| x | Single | La coordenada X para el lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para el lado superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |
| createFromTemplate | Boolean | Si es verdadero, entonces la nueva forma se ajustará desde la plantilla predeterminada. Se asignará un nombre no vacío, estilo simple y texto centrado a la nueva forma. Si es falso, entonces todos los valores de las propiedades de la nueva forma tendrán valores predeterminados. |

### Valor de Retorno

Objeto AutoShape creado.

### Véase También

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->