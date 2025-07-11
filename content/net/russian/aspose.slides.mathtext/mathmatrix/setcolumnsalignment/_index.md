---
title: SetColumnsAlignment
second_title: Aspose.Slides для .NET API Reference
description: Установить горизонтальное выравнивание указанных столбцов
type: docs
weight: 210
url: /ru/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---

## MathMatrix.SetColumnsAlignment метод

Установить горизонтальное выравнивание указанных столбцов

```csharp
public void SetColumnsAlignment(int columnIndex, uint columnsCount, MathHorizontalAlignment val)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | Int32 | Индекс первого столбца для установки выравнивания (начиная с нуля) |
| columnsCount | UInt32 | Количество столбцов для задания выравнивания |
| val | MathHorizontalAlignment | Новое значение горизонтального выравнивания указанного столбца |

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.SetColumnAlignment(0, 3, MathHorizontalAlignment.Left);
```

### Смотрите также

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)
* class [MathMatrix](../../mathmatrix)
* namespace [Aspose.Slides.MathText](../../mathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->