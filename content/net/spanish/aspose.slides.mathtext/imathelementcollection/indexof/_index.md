---
title: IndexOf
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina el índice de un elemento matemático específico en la colección.
type: docs
weight: 80
url: /es/aspose.slides.mathtext/imathelementcollection/indexof/
---

## Método IMathElementCollection.IndexOf

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
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
int index = collection.IndexOf(plusElement);
```

### Ver También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->