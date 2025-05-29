---
title: ParentShape
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve la forma padre o null si el objeto padre no implementa la interfaz IShape Solo lectura IShapeaspose.slides/ishape.
type: docs
weight: 50
url: /es/aspose.slides/itextframe/parentshape/
---

## Propiedad ITextFrame.ParentShape

Devuelve la forma padre o null si el objeto padre no implementa la interfaz IShape Solo lectura [`IShape`](../../ishape).

```csharp
public IShape ParentShape { get; }
```

### Ejemplos

El siguiente fragmento de código muestra

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
    AutoShape autoShape = (AutoShape)presentation.Slides[0].Shapes[0];
    
    Assert.IsTrue(autoShape.TextFrame.ParentShape == autoShape);
    // ...
}
```

### Véase también

* interfaz [IShape](../../ishape)
* interfaz [ITextFrame](../../itextframe)
* espacio de nombres [Aspose.Slides](../../itextframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->