---
title: Insertar
second_title: Referencia de API de Aspose.Slides para .NET
description: Inserta un elemento matemático en la colección en el índice especificado.
type: docs
weight: 90
url: /es/aspose.slides.mathtext/imathelementcollection/insert/
---

## Método IMathElementCollection.Insert

Inserta un elemento matemático en la colección en el índice especificado.

```csharp
public void Insert(int index, IMathElement item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar IMathElement. |
| item | IMathElement | El IMathElement para insertar. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Vea También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->