---
title: AddAutoShape
second_title: Aspose.Slides para .NET API Reference
description: Crea una nueva AutoShape, la ajusta desde la plantilla predeterminada y la agrega al final de la colección.
type: docs
weight: 90
url: /es/aspose.slides/shapecollection/addautoshape/
---

## AddAutoShape(ShapeType, float, float, float, float) {#addautoshape}

Crea una nueva AutoShape, la ajusta desde la plantilla predeterminada y la agrega al final de la colección.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | ShapeType | El [`ShapeType`](../../shapetype) de la forma. |
| x | Single | La coordenada X para un lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para un lado superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |

### Valor de retorno

Objeto AutoShape creado.

### Véase también

* interfaz [IAutoShape](../../iautoshape)
* enumeración [ShapeType](../../shapetype)
* clase [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* ensamblado [Aspose.Slides](../../../)

---

## AddAutoShape(ShapeType, float, float, float, float, bool) {#addautoshape_1}

Crea una nueva AutoShape y la agrega al final de la colección.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, 
    bool createFromTemplate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | ShapeType | El [`ShapeType`](../../shapetype) de la forma. |
| x | Single | La coordenada X para un lado izquierdo del marco de la forma. |
| y | Single | La coordenada Y para un lado superior del marco de la forma. |
| width | Single | El ancho del marco de la forma. |
| height | Single | La altura del marco de la forma. |
| createFromTemplate | Boolean | Si es verdadero, entonces la nueva forma se ajustará desde la plantilla predeterminada. Se asignará un nombre no vacío, un estilo simple y texto centrado a la nueva forma. Si es falso, entonces todos los valores de las propiedades de la nueva forma tendrán valores predeterminados. |

### Valor de retorno

Objeto AutoShape creado.

### Véase también

* interfaz [IAutoShape](../../iautoshape)
* enumeración [ShapeType](../../shapetype)
* clase [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->