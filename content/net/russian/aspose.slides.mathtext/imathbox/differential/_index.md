---
title: Differential
second_title: Aspose.Sildes для .NET API Справочник
description: Дифференциальный. Когда истинно, коробка действует как дифференциал, например, в интеграле и получает соответствующее горизонтальное расстояние для математического дифференциала. По умолчанию ложь
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathbox/differential/
---

## IMathBox.Differential свойство

Дифференциальный. Когда истинно, коробка действует как дифференциал (например, 𝑑𝑥 в интеграле) и получает соответствующее горизонтальное расстояние для математического дифференциала. По умолчанию: ложь

```csharp
public bool Differential { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
IMathBox differential = new MathematicalText("dx").ToBox();
differential.Differential = true;
IMathBlock baseArg = new MathematicalText("x").Join(differential);
IMathNaryOperator integral = baseArg.Integral(MathIntegralTypes.Simple, "0", "1");
```

### См. также

* интерфейс [IMathBox](../../imathbox)
* пространство имен [Aspose.Slides.MathText](../../imathbox)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->