---
title: Item
second_title: Справочник по API Aspose.Slides для .NET
description: Элемент матрицы
type: docs
weight: 70
url: /ru/aspose.slides.mathtext/mathmatrix/item/
---
## MathMatrix indexer

Элемент матрицы

```csharp
public IMathElement this[int row, int column] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| row | Отсчитываемый от нуля индекс матрицы строка для получения элемента |
| column | Отсчитываемый от нуля индекс столбца для получения элемента |

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Смотрите также

* interface [IMathElement](../../imathelement)
* class [MathMatrix](../../mathmatrix)
* пространство имен [Aspose.Slides.MathText](../../mathmatrix)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
