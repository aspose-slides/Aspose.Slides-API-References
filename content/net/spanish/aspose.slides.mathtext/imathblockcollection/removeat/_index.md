---
title: RemoveAt
second_title: Referencia de la API de Aspose.Slides para .NET
description: Elimina un elemento en el índice especificado de la colección.
type: docs
weight: 100
url: /es/aspose.slides.mathtext/imathblockcollection/removeat/
---

## Método IMathBlockCollection.RemoveAt

Elimina un elemento en el índice especificado de la colección.

```csharp
public void RemoveAt(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero del elemento a eliminar. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
blockCollection.RemoveAt(0);
```

### Véase También

* interfaz [IMathBlockCollection](../../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathblockcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->