---
title: Elemento
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene el elemento en el índice especificado. Solo lectura IMathBlockaspose.slides.mathtext/imathblock.
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathblockcollection/item/
---

## Índice de IMathBlockCollection

Obtiene el elemento en el índice especificado. Solo lectura [`IMathBlock`](../../imathblock).

```csharp
public IMathBlock this[int index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | El índice basado en cero del elemento a obtener |

### Valor de Retorno

El bloque de un texto matemático.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
blockCollection.Add(new MathBlock(new MathematicalText("block1")));
blockCollection.Add(new MathBlock(new MathematicalText("block2")));
IMathBlock block = blockCollection[1];
```

### Vea También

* interfaz [IMathBlock](../../imathblock)
* interfaz [IMathBlockCollection](../../imathblockcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathblockcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->