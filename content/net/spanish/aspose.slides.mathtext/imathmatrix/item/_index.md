---
title: Item
second_title: Referencia de la API de Aspose.Slides para .NET
description: Elementos de la matriz
type: docs
weight: 70
url: /es/aspose.slides.mathtext/imathmatrix/item/
---

## IMathMatrix indexer

Elementos de la matriz

```csharp
public IMathElement this[int row, int column] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| row | El índice basado en cero de la fila para obtener el elemento |
| column | El índice basado en cero de la columna para obtener el elemento |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Ver También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathMatrix](../../imathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../imathmatrix)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->