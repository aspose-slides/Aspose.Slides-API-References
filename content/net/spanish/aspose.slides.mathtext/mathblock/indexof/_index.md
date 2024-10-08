---
title: IndexOf
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina el índice de un elemento matemático específico en la colección.
type: docs
weight: 120
url: /es/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock.IndexOf method

Determina el índice de un elemento matemático específico en la colección.

```csharp
public int IndexOf(IMathElement item)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| item | IMathElement | El elemento a ubicar en la colección. |

### Valor_devuelto

El índice de*item* si se encuentra en la colección; de lo contrario, -1.

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
int index = mathBlock.IndexOf(plusElement);
```

### Ver también

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
