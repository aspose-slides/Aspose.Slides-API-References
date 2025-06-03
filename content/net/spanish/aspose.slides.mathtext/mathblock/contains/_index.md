---
title: Contains
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina si la colección contiene un valor específico.
type: docs
weight: 70
url: /es/aspose.slides.mathtext/mathblock/contains/
---

## Método MathBlock.Contains

Determina si la colección contiene un valor específico.

```csharp
public bool Contains(IMathElement item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathElement | El objeto que se localizará en la colección. |

### Valor de Retorno

true si *item* se encuentra en la colección; de lo contrario, false.

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
bool contains = mathBlock.Contains(plusElement);
```

### Ver También

* interfaz [IMathElement](../../imathelement)
* clase [MathBlock](../../mathblock)
* espacio de nombres [Aspose.Slides.MathText](../../mathblock)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->