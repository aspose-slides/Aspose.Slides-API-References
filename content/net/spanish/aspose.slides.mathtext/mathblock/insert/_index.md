---
title: Insert
second_title: Referencia de la API de Aspose.Slides para .NET
description: Inserta un MathElement en la colección en el índice especificado.
type: docs
weight: 130
url: /es/aspose.slides.mathtext/mathblock/insert/
---

## MathBlock.Insert método

Inserta un MathElement en la colección en el índice especificado.

```csharp
public void Insert(int index, IMathElement item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el MathElement. |
| item | IMathElement | El MathElement a insertar. |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Ver También

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namespace [Aspose.Slides.MathText](../../mathblock)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->