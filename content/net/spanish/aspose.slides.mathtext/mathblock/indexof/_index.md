---
title: IndexOf
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina el índice de un elemento matemático específico en la colección.
type: docs
weight: 120
url: /es/aspose.slides.mathtext/mathblock/indexof/
---

## Método MathBlock.IndexOf

Determina el índice de un elemento matemático específico en la colección.

```csharp
public int IndexOf(IMathElement item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathElement | El elemento a localizar en la colección. |

### Valor de Retorno

El índice de *item* si se encuentra en la colección; de lo contrario, -1.

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

### Vea También

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namespace [Aspose.Slides.MathText](../../mathblock)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->