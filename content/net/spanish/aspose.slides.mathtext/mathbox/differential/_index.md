---
title: Diferencial
second_title: Referencia de API de Aspose.Slides para .NET
description: Diferencial Cuando es verdadero, la caja actúa como un diferencial, por ejemplo, en un integrando y recibe el espaciado horizontal adecuado para el diferencial matemático. Predeterminado: falso
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathbox/differential/
---

## Propiedad MathBox.Differential

Diferencial Cuando es verdadero, la caja actúa como un diferencial (por ejemplo, 𝑑𝑥 en un integrando), y recibe el espaciado horizontal adecuado para el diferencial matemático. Predeterminado: falso

```csharp
public bool Differential { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBox differential = new MathematicalText("dx").ToBox();
differential.Differential = true;
IMathBlock baseArg = new MathematicalText("x").Join(differential);
IMathNaryOperator integral = baseArg.Integral(MathIntegralTypes.Simple, "0", "1");
```

### Véase también

* clase [MathBox](../../mathbox)
* espacio de nombres [Aspose.Slides.MathText](../../mathbox)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->