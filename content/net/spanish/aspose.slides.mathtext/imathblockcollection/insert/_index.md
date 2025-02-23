---
title: Insert
second_title: Referencia de la API de Aspose.Slides para .NET
description: Inserta IMathBlock en la colección en el índice especificado.
type: docs
weight: 80
url: /es/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection.Insert method

Inserta IMathBlock en la colección en el índice especificado.

```csharp
public void Insert(int index, IMathBlock item)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero en el que se debe insertar un elemento. |
| item | IMathBlock | El IMathBlock para insertar. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Insert(0, block);
```

### Ver también

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathblockcollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
