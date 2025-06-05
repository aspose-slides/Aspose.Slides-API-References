---
title: IAutoShape
second_title: Aspose.Sildes para .NET API Reference
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
| [UseBackgroundFill](../../aspose.slides/iautoshape/usebackgroundfill) { get; set; } | Determina si este autoshape debe ser relleno con el relleno de fondo de la diapositiva en lugar del especificado por el estilo o formato de relleno. Lectura/escritura Booleano. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddTextFrame](../../aspose.slides/iautoshape/addtextframe)(string) | Agrega un nuevo TextFrame a una forma. Si la forma ya tiene un TextFrame, simplemente cambia su texto. |

### Véase También

* interfaz [IGeometryShape](../igeometryshape)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->