---
title: BaseJustification
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica la alineación de la matriz en relación con el texto circundante El texto fuera de la matriz se puede alinear con la parte inferior superior o central de un objeto de matriz. Valor predeterminado Center
type: docs
weight: 30
url: /es/net/aspose.slides.mathtext/imatharray/basejustification/
---
## IMathArray.BaseJustification property

Especifica la alineación de la matriz en relación con el texto circundante El texto fuera de la matriz se puede alinear con la parte inferior, superior o central de un objeto de matriz. Valor predeterminado: Center

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

### Ver también

* enum [MathVerticalAlignment](../../mathverticalalignment)
* interface [IMathArray](../../imatharray)
* espacio de nombres [Aspose.Slides.MathText](../../imatharray)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->