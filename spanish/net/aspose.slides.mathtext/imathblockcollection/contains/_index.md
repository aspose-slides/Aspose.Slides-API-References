---
title: Contains
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina si la colección contiene un valor específico.
type: docs
weight: 60
url: /es/net/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection.Contains method

Determina si la colección contiene un valor específico.

```csharp
public bool Contains(IMathBlock item)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| item | IMathBlock | El objeto que se va a ubicar en la colección. |

### Valor_devuelto

verdadero si*item* se encuentra en la colección; de lo contrario, false.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
bool contains = blockCollection.Contains(block);
```

### Ver también

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathblockcollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->