---
title: GrowToMatchOperandHeight
second_title: Referencia de API Aspose.Slides para .NET
description: El carácter operador crece verticalmente para igualar la altura de su operando
type: docs
weight: 10
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/growtomatchoperandheight/
---

## IMathNaryOperatorProperties.GrowToMatchOperandHeight property

El carácter operador crece verticalmente para igualar la altura de su operando

```csharp
public bool GrowToMatchOperandHeight { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
naryOperator.GrowToMatchOperandHeight = true;
```

### Véase también

* interface [IMathNaryOperatorProperties](../../imathnaryoperatorproperties)
* namespace [Aspose.Slides.MathText](../../imathnaryoperatorproperties)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->