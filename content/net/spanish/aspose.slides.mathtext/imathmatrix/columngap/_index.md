---
title: ColumnGap
second_title: Referencia de la API Aspose.Slides para .NET
description: El valor del espaciado horizontal entre las columnas de una matriz. Si el ColumnGapRule se establece en 3 "Exactamente", entonces la unidad se interpreta como twips 1/20 de un punto. Si el ColumnGapRule se establece en 4 "Múltiple", entonces la unidad se interpreta como el número de incrementos de 0.5 em. En otros casos es ignorado. Predeterminado: 0
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathmatrix/columngap/
---

## Propiedad IMathMatrix.ColumnGap

El valor del espaciado horizontal entre las columnas de una matriz; Si el ColumnGapRule se establece en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto). Si el ColumnGapRule se establece en 4 ("Múltiple"), entonces la unidad se interpreta como el número de incrementos de 0.5 em. En otros casos es ignorado. Predeterminado: 0

```csharp
public uint ColumnGap { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.ColumnGapRule = MathSpacingRules.Exactly;
matrix.ColumnGap = 20;
```

### Ver También

* interfaz [IMathMatrix](../../imathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../imathmatrix)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->