---
title: Contains
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si la colección contiene un valor específico.
type: docs
weight: 60
url: /es/aspose.slides.mathtext/imathelementcollection/contains/
---

## Método IMathElementCollection.Contains

Determina si la colección contiene un valor específico.

```csharp
public bool Contains(IMathElement item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | IMathElement | El objeto a localizar en la colección. |

### Valor de Retorno

true si *item* se encuentra en la colección; de lo contrario, false.

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
bool contains = collection.Contains(plusElement);
```

### Ver También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->