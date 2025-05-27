---
title: ColumnGap
second_title: Referencia de API de Aspose.Slides para .NET
description: El valor del espaciado horizontal entre columnas de una matriz. Si la ColumnGapRule está configurada en 3 "Exactamente", entonces la unidad se interpreta como twips 1/20 de un punto. Si la ColumnGapRule está configurada en 4 "Múltiple", entonces la unidad se interpreta como el número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathmatrix/columngap/
---

## Propiedad MathMatrix.ColumnGap

El valor del espaciado horizontal entre columnas de una matriz; si la ColumnGapRule está configurada en 3 ("Exactamente"), entonces la unidad se interpreta como twips (1/20 de un punto). Si la ColumnGapRule está configurada en 4 ("Múltiple"), entonces la unidad se interpreta como el número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0

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

### Véase También

* clase [MathMatrix](../../mathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../mathmatrix)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->