---
title: ColumnGap
second_title: Aspose.Slides для .NET API Reference
description: Значение горизонтального расстояния между столбцами матрицы. Если ColumnGapRule установлено на 3 "Exactly", то единица измерения интерпретируется как твипы 1/20 пункта. Если ColumnGapRule установлено на 4 "Multiple", то единица измерения интерпретируется как количество увеличений на 0,5 em. В других случаях игнорируется. Значение по умолчанию 0.
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathmatrix/columngap/
---

## MathMatrix.ColumnGap свойство

Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлено на 3 ("Exactly"), то единица измерения интерпретируется как твипы (1/20 пункта). Если ColumnGapRule установлено на 4 ("Multiple"), то единица измерения интерпретируется как количество увеличений на 0,5 em. В других случаях игнорируется. Значение по умолчанию: 0.

```csharp
public uint ColumnGap { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.ColumnGapRule = MathSpacingRules.Exactly;
matrix.ColumnGap = 20;
```

### См. также

* класс [MathMatrix](../../mathmatrix)
* пространство имен [Aspose.Slides.MathText](../../mathmatrix)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->