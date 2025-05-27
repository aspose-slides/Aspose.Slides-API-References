---
title: Ítem
second_title: Referencia de API de Aspose.Slides para .NET
description: Elementos de la matriz
type: docs
weight: 70
url: /es/aspose.slides.mathtext/imathmatrix/item/
---

## Indexador IMathMatrix

Elementos de la matriz

```csharp
public IMathElement this[int row, int column] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| row | El índice basado en cero de la fila para obtener el ítem |
| column | El índice basado en cero de la columna para obtener el ítem |

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