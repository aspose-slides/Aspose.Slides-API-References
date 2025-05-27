---
title: Contiene
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si la colección contiene un valor específico.
type: docs
weight: 60
url: /es/aspose.slides.mathtext/imathblockcollection/contains/
---

## Método IMathBlockCollection.Contains

Determina si la colección contiene un valor específico.

```csharp
public bool Contains(IMathBlock item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathBlock | El objeto a localizar en la colección. |

### Valor de Retorno

true si *item* se encuentra en la colección; de lo contrario, false.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
bool contains = blockCollection.Contains(block);
```

### Véase También

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* namespace [Aspose.Slides.MathText](../../imathblockcollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->