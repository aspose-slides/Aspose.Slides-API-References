---
title: RowGap
second_title: Referencia de la API de Aspose.Slides para .NET
description: El valor del espaciado vertical entre filas de una matriz. Si la RowGapRule se establece en 3 "Exactamente", entonces la unidad se interpreta como twips 1/20 de un punto. Si la RowGapRule se establece en 4 "Múltiple", entonces la unidad se interpreta como media línea. Por defecto 0
type: docs
weight: 100
url: /es/aspose.slides.mathtext/imathmatrix/rowgap/
---

## Propiedad IMathMatrix.RowGap

El valor del espaciado vertical entre filas de una matriz; Si la RowGapRule se establece en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto). Si la RowGapRule se establece en 4 ("Múltiple"), entonces la unidad se interpreta como media línea. Por defecto: 0

```csharp
public uint RowGap { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.RowGapRule = MathSpacingRules.Exactly;
matrix.RowGap = 20;
```

### Ver También

* interfaz [IMathMatrix](../../imathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../imathmatrix)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->