---
title: Item
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene el elemento en el índice especificado. Solo lecturaIMathElementaspose.slides.mathtext/imathelement .
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathelementcollection/item/
---
## IMathElementCollection indexer

Obtiene el elemento en el índice especificado. Solo lectura[`IMathElement`](../../imathelement) .

```csharp
public IMathElement this[int index] { get; }
```

| Parámetro | Descripción |
| --- | --- |
| index | El índice de base cero del elemento que se va a obtener |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
IMathElement firstElem = collection[0];
```

### Ver también

* interface [IMathElement](../../imathelement)
* interface [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
