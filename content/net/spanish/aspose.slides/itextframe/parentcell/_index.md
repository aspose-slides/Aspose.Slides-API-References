---
title: ParentCell
second_title: Referencia de la API Aspose.Slides para .NET
description: Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. Solo lectura ICellaspose.slides/icell.
type: docs
weight: 40
url: /es/aspose.slides/itextframe/parentcell/
---

## Propiedad ITextFrame.ParentCell

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

### También Vea

* interfaz [ICell](../../icell)
* interfaz [ITextFrame](../../itextframe)
* espacio de nombres [Aspose.Slides](../../itextframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->