---
title: ParentShape
second_title: Aspose.Sildes para .NET Referencia de API
description: Devuelve la forma padre o nulo si el objeto padre no implementa la interfaz IShape Solo lectura IShapeaspose.slides/ishape.
type: docs
weight: 40
url: /es/aspose.slides/textframe/parentshape/
---

## Propiedad TextFrame.ParentShape

Devuelve la forma padre o nulo si el objeto padre no implementa la interfaz IShape Solo lectura [`IShape`](../../ishape).

```csharp
public IShape ParentShape { get; }
```

### Ejemplos

El siguiente ejemplo de código muestra

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
    AutoShape autoShape = (AutoShape)presentation.Slides[0].Shapes[0];
    
    Assert.IsTrue(autoShape.TextFrame.ParentShape == autoShape);
    // ...
}
```

### Véase También

* interfaz [IShape](../../ishape)
* clase [TextFrame](../../textframe)
* espacio de nombres [Aspose.Slides](../../textframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->