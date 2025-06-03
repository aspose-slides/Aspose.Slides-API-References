---
title: Add
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega un elemento matemático al final de la colección.
type: docs
weight: 50
url: /es/aspose.slides.mathtext/mathblock/add/
---

## Método MathBlock.Add

Agrega un elemento matemático al final de la colección.

```csharp
public void Add(IMathElement item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathElement | El IMathElement que se agregará al final de la colección. |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
mathBlock.Add(new MathematicalText("+"));
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### También Vea

* interfaz [IMathElement](../../imathelement)
* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->