---
title: RemoveAt
second_title: Aspose.Sildes para .NET Referencia de la API
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 110
url: /es/aspose.slides.mathtext/imathelementcollection/removeat/
---

## IMathElementCollection.RemoveAt método

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
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
collection.RemoveAt(2);
```

### Ver También

* interface [IMathElementCollection](../../imathelementcollection)
* namespace [Aspose.Slides.MathText](../../imathelementcollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->