---
title: DeleteRow
second_title: Справочник по API Aspose.Slides для .NET
description: Удаляет указанную строку
type: docs
weight: 130
url: /ru/net/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix.DeleteRow method

Удаляет указанную строку

```csharp
public void DeleteRow(int rowIndex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | Int32 | Отсчитываемый от нуля индекс строку для удаления. |

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | При попытке удалить последнюю одиночную строку в матрице |
| ArgumentOutOfRangeException | Если rowIndex меньше нуля или больше или равен RowCount |

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.DeleteRow(0);
```

### Смотрите также

* class [MathMatrix](../../mathmatrix)
* пространство имен [Aspose.Slides.MathText](../../mathmatrix)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->