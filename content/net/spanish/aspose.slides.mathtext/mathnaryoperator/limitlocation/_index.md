---
title: LimitLocation
second_title: Referencia de API de Aspose.Slides para .NET
description: La ubicación de límites subíndices y superíndices
type: docs
weight: 60
url: /es/aspose.slides.mathtext/mathnaryoperator/limitlocation/
---

## Propiedad MathNaryOperator.LimitLocation

La ubicación de límites (subíndice y superíndice)

```csharp
public MathLimitLocations LimitLocation { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
naryOperator.LimitLocation = MathLimitLocations.SubscriptSuperscript;
```

### Véase también

* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathNaryOperator](../../mathnaryoperator)
* namespace [Aspose.Slides.MathText](../../mathnaryoperator)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->