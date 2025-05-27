---
title: RemoveAt
second_title: Referencia de la API de Aspose.Slides para .NET
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 110
url: /es/aspose.slides.mathtext/imathelementcollection/removeat/
---

## Método IMathElementCollection.RemoveAt

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

### Véase también

* interfaz [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->