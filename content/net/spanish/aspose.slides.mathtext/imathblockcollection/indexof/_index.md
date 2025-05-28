---
title: IndexOf
second_title: Aspose.Slides para .NET Referencia de API
description: Determina el índice de un IMathBlock específico en la colección.
type: docs
weight: 70
url: /es/aspose.slides.mathtext/imathblockcollection/indexof/
---

## Método IMathBlockCollection.IndexOf

Determina el índice de un IMathBlock específico en la colección.

```csharp
public int IndexOf(IMathBlock item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathBlock | El elemento a localizar en la colección. |

### Valor de Retorno

El índice de *item* si se encuentra en la colección; de lo contrario, -1.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
int index = blockCollection.IndexOf(block);
```

### Véase También

* interfaz [IMathBlock](../../imathblock)
* interfaz [IMathBlockCollection](../../imathblockcollection)
* namespace [Aspose.Slides.MathText](../../imathblockcollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->