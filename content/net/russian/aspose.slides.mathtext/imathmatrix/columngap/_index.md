---
title: ColumnGap
second_title: Aspose.Slides для .NET API Справочник
description: Значение горизонтального расстояния между столбцами матрицы. Если ColumnGapRule установлено на 3 "Точно", то единица измерения интерпретируется как твипсы 1/20 точки. Если ColumnGapRule установлено на 4 "Множественное", то единица измерения интерпретируется как количество увеличений на 0.5 em. В других случаях игнорируется. По умолчанию 0
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathmatrix/columngap/
---

## IMathMatrix.ColumnGap свойство

Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлено на 3 ("Точно"), то единица измерения интерпретируется как твипсы (1/20 точки). Если ColumnGapRule установлено на 4 ("Множественное"), то единица измерения интерпретируется как количество увеличений на 0.5 em. В других случаях игнорируется. По умолчанию: 0

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

* интерфейс [IMathMatrix](../../imathmatrix)
* пространство имен [Aspose.Slides.MathText](../../imathmatrix)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->