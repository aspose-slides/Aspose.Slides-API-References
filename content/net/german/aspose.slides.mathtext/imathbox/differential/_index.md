---
title: Differential
second_title: Aspose.Slides für .NET API Referenz
description: Differential. Wenn wahr, fungiert die Box als Differential, z. B. 𝑑𝑥 in einem Integranden, und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard false
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathbox/differential/
---

## IMathBox.Differential Eigenschaft

Differential. Wenn wahr, fungiert die Box als Differential (z. B. 𝑑𝑥 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false

```csharp
public bool Differential { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
IMathBox differential = new MathematicalText("dx").ToBox();
differential.Differential = true;
IMathBlock baseArg = new MathematicalText("x").Join(differential);
IMathNaryOperator integral = baseArg.Integral(MathIntegralTypes.Simple, "0", "1");
```

### Siehe auch

* Schnittstelle [IMathBox](../../imathbox)
* Namensraum [Aspose.Slides.MathText](../../imathbox)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->