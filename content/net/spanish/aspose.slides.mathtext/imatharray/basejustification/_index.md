---
title: BaseJustification
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica la alineación de la matriz en relación con el texto circundante. El texto fuera de la matriz se puede alinear con la parte inferior, la parte superior o el centro de un objeto de matriz. Valor predeterminado Centro
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imatharray/basejustification/
---

## IMathArray.BaseJustification property

Especifica la alineación de la matriz en relación con el texto circundante. El texto fuera de la matriz se puede alinear con la parte inferior, la parte superior o el centro de un objeto de matriz. Valor predeterminado: Centro

```csharp
public MathVerticalAlignment BaseJustification { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
mathArray.BaseJustification = MathVerticalAlignment.Top;
```

### También Vea

* enum [MathVerticalAlignment](../../mathverticalalignment)
* interface [IMathArray](../../imatharray)
* namespace [Aspose.Slides.MathText](../../imatharray)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->