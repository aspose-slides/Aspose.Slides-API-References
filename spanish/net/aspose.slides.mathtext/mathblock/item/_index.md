---
title: Item
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene o establece IMathElement en el índice especificado.
type: docs
weight: 40
url: /es/net/aspose.slides.mathtext/mathblock/item/
---
## MathBlock indexer

Obtiene o establece IMathElement en el índice especificado.

```csharp
public IMathElement this[int index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | El índice de base cero del elemento. |

### Valor_devuelto

El elemento matemático.

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
IMathElement firstElem = mathBlock[0];
```

### Ver también

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->