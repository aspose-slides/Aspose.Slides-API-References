---
title: Contains
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si la colección contiene un valor específico.
type: docs
weight: 60
url: /es/aspose.slides.mathtext/imathblockcollection/contains/
---

## IMathBlockCollection.Contains método

Determina si la colección contiene un valor específico.

```csharp
public bool Contains(IMathBlock item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathBlock | El objeto a localizar en la colección. |

### Valor de retorno

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

### Véase también

* interfaz [IMathBlock](../../imathblock)
* interfaz [IMathBlockCollection](../../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathblockcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->