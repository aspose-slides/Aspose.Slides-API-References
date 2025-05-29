---
title: IAutoShape
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un AutoShape.
type: docs
weight: 5040
url: /es/aspose.slides/iautoshape/
---

## Interfaz IAutoShape

Representa un AutoShape.

```csharp
public interface IAutoShape : IGeometryShape
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIGeometryShape](../../aspose.slides/iautoshape/asigeometryshape) { get; } | Permite obtener la interfaz base IGeometryShape. Solo lectura [`IGeometryShape`](../igeometryshape). |
| [AutoShapeLock](../../aspose.slides/iautoshape/autoshapelock) { get; } | Devuelve los bloqueos del AutoShape. Solo lectura [`IAutoShapeLock`](../iautoshapelock). |
| [IsTextBox](../../aspose.slides/iautoshape/istextbox) { get; } | Especifica si la forma es un cuadro de texto. |
| [ShapeLock](../../aspose.slides/iautoshape/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IAutoShapeLock`](../iautoshapelock). |
| [TextFrame](../../aspose.slides/iautoshape/textframe) { get; } | Devuelve el objeto TextFrame para el AutoShape. Solo lectura [`ITextFrame`](../itextframe). |
| [UseBackgroundFill](../../aspose.slides/iautoshape/usebackgroundfill) { get; set; } | Determina si este autoshape debe ser rellenado con el relleno de fondo de la diapositiva en lugar de lo especificado por el estilo o formato de relleno. Booleano de lectura/escritura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddTextFrame](../../aspose.slides/iautoshape/addtextframe)(string) | Agrega un nuevo TextFrame a una forma. Si la forma ya tiene un TextFrame, simplemente cambia su texto. |

### Véase también

* interfaz [IGeometryShape](../igeometryshape)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->