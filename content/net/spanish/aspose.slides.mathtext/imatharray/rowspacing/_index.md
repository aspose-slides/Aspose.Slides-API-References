---
title: RowSpacing
second_title: Referencia de API de Aspose.Slides para .NET
description: Espaciado entre filas de un arreglo. Se utiliza solo cuando RowSpacingRule se establece en 3. Exactamente en cuyo caso la unidad de medida son puntos o Múltiple en cuyo caso la unidad de medida son medias líneas. Predeterminado: 0
type: docs
weight: 60
url: /es/aspose.slides.mathtext/imatharray/rowspacing/
---

## Propiedad IMathArray.RowSpacing

Espaciado entre filas de un arreglo. Se utiliza solo cuando RowSpacingRule se establece en 3. Exactamente en cuyo caso la unidad de medida son puntos o Múltiple en cuyo caso la unidad de medida son medias líneas. Predeterminado: 0

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

* interfaz [IMathArray](../../imatharray)
* espacio de nombres [Aspose.Slides.MathText](../../imatharray)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->