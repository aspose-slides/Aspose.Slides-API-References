---
title: SetColumnAlignment
second_title: Aspose.Sildes для .NET API Справочник
description: Установите горизонтальное выравнивание указанного столбца
type: docs
weight: 200
url: /ru/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---

## MathMatrix.SetColumnAlignment метод

Установите горизонтальное выравнивание указанного столбца

```csharp
public void SetColumnAlignment(int columnIndex, MathHorizontalAlignment val)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | Int32 | Индекс столбца, начинающийся с нуля |
| val | MathHorizontalAlignment | Новое значение горизонтального выравнивания указанного столбца |

### Примеры

Пример:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.SetColumnAlignment(0, MathHorizontalAlignment.Left);
```

### См. также

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)
* class [MathMatrix](../../mathmatrix)
* namespace [Aspose.Slides.MathText](../../mathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->