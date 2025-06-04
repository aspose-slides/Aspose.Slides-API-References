---
title: RowSpacing
second_title: Aspose.Sildes для .NET API Справочник
description: Расстояние между рядами массива. Используется только когда RowSpacingRule установлено на 3. В этом случае единица измерения – пункты, или Multiple, в этом случае единица измерения – полустроки. По умолчанию 0.
type: docs
weight: 60
url: /ru/aspose.slides.mathtext/matharray/rowspacing/
---

## MathArray.RowSpacing свойство

Расстояние между рядами массива. Используется только когда RowSpacingRule установлено на 3. В этом случае единица измерения – пункты, или Multiple, в этом случае единица измерения – полустроки. По умолчанию: 0

```csharp
public uint RowSpacing { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
mathArray.RowSpacingRule = MathRowSpacingRule.Exactly;
mathArray.RowSpacing = 10;
```

### См. Также

* класс [MathArray](../../matharray)
* пространство имен [Aspose.Slides.MathText](../../matharray)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->