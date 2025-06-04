---
title: Count
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene el número de elementos que realmente contiene la colección. Solo lectura Int32.
type: docs
weight: 20
url: /es/aspose.slides.mathtext/imathblockcollection/count/
---

## IMathBlockCollection.Count property

Obtiene el número de elementos que realmente contiene la colección. Solo lectura Int32.

```csharp
public int Count { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
blockCollection.Add(new MathBlock(new MathematicalText("block1")));
blockCollection.Add(new MathBlock(new MathematicalText("block2")));
int blocksCount = blockCollection.Count;
```

### Véase también

* interfaz [IMathBlockCollection](../../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathblockcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->