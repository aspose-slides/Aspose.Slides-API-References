---
title: Item
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene el elemento en el índice especificado. Solo lectura IMathElementaspose.slides.mathtext/imathelement.
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathelementcollection/item/
---

## Indexador IMathElementCollection

Obtiene el elemento en el índice especificado. Solo lectura [`IMathElement`](../../imathelement).

```csharp
public IMathElement this[int index] { get; }
```

| Parámetro | Descripción |
| --- | --- |
| index | El índice basado en cero del elemento a obtener |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
IMathElement firstElem = collection[0];
```

### Véase También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathElementCollection](../../imathelementcollection)
* espacio de nombres [Aspose.Slides.MathText](../../imathelementcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->