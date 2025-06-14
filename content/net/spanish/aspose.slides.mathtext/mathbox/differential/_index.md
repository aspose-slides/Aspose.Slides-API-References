---
title: Differential
second_title: Aspose.Sildes para .NET Referencia de la API
description: Differential Cuando es verdadero, la caja actúa como un diferencial, por ejemplo, en un integrando y recibe el espaciado horizontal adecuado para el diferencial matemático. Por defecto falso
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathbox/differential/
---

## MathBox.Differential property

Differential Cuando es verdadero, la caja actúa como un diferencial (por ejemplo, 𝑑𝑥 en un integrando) y recibe el espaciado horizontal adecuado para el diferencial matemático. Por defecto: falso

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

### Ver También

* clase [MathBox](../../mathbox)
* espacio de nombres [Aspose.Slides.MathText](../../mathbox)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
