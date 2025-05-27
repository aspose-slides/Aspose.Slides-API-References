---
title: EspaciadoFilas
second_title: Referencia de API de Aspose.Slides para .NET
description: Espaciado entre filas de un array. Se utiliza solo cuando RowSpacingRule está establecido en 3. Exactamente en qué caso la unidad de medida son puntos o Múltiple en qué caso la unidad de medida son media líneas. Predeterminado: 0
type: docs
weight: 60
url: /es/aspose.slides.mathtext/matharray/rowspacing/
---

## Propiedad MathArray.RowSpacing

Espaciado entre filas de un array. Se utiliza solo cuando RowSpacingRule está establecido en 3. Exactamente en qué caso la unidad de medida son puntos o Múltiple en qué caso la unidad de medida son media líneas. Predeterminado: 0

```csharp
public uint RowSpacing { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
mathArray.RowSpacingRule = MathRowSpacingRule.Exactly;
mathArray.RowSpacing = 10;
```

### Véase También

* clase [MathArray](../../matharray)
* espacio de nombres [Aspose.Slides.MathText](../../matharray)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->