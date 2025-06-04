---
title: RemoveAt
second_title: Aspose.Sildes para .NET Referencia de API
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 170
url: /es/aspose.slides.mathtext/mathblock/removeat/
---

## MathBlock.RemoveAt método

Elimina el elemento en el índice especificado de la colección.

```csharp
public void RemoveAt(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero del elemento a eliminar. |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
mathBlock.RemoveAt(2);
```

### Ver También

* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->