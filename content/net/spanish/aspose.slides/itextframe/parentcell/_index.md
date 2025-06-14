---
title: ParentCell
second_title: Aspose.Slides para .NET API Reference
description: Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. Solo lectura ICellaspose.slides/icell.
type: docs
weight: 40
url: /es/aspose.slides/itextframe/parentcell/
---

## ITextFrame.ParentCell propiedad

Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. Solo lectura [`ICell`](../../icell).

```csharp
public ICell ParentCell { get; }
```

### Ejemplos

El siguiente ejemplo de código muestra

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
    Table table = (Table)presentation.Slides[0].Shapes[0];
    
    Assert.IsTrue(table[0,0].TextFrame.ParentCell == table[0,0]);
    // ...
}
```

### Ver También

* interfaz [ICell](../../icell)
* interfaz [ITextFrame](../../itextframe)
* namespace [Aspose.Slides](../../itextframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->