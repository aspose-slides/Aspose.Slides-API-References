---
title: Operator
second_title: Referencia de la API Aspose.Slides para .NET
description: Carácter del operador nario, por ejemplo
type: docs
weight: 50
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/operator/
---

## IMathNaryOperatorProperties.Operator property

Carácter del operador nario, por ejemplo: '∑', '∫'

```csharp
public char Operator { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
char operatorSymbol = naryOperator.Operator;
```

### Véase también

* interfaz [IMathNaryOperatorProperties](../../imathnaryoperatorproperties)
* espacio de nombres [Aspose.Slides.MathText](../../imathnaryoperatorproperties)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
