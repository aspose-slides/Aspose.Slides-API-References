---
title: RowGap
second_title: Aspose.Slides para .NET Referencia de API
description: El valor del espacio vertical entre filas de una matriz Si el RowGapRule se establece en 3 "Exactamente", entonces la unidad se interpreta como twips 1/20 de un punto Si el RowGapRule se establece en 4 "Múltiple", entonces la unidad se interpreta como media línea. Predeterminado 0
type: docs
weight: 100
url: /es/aspose.slides.mathtext/mathmatrix/rowgap/
---

## Propiedad MathMatrix.RowGap

El valor del espacio vertical entre filas de una matriz; Si el RowGapRule se establece en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto) Si el RowGapRule se establece en 4 ("Múltiple"), entonces la unidad se interpreta como media línea. Predeterminado: 0

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

### Véase también

* clase [MathMatrix](../../mathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../mathmatrix)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->