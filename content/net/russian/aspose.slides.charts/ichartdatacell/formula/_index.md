---
title: Formula
second_title: Справочник по API Aspose.Sildes для .NET
description: Получает или задает формулу в стиле A1.
type: docs
weight: 40
url: /ru/aspose.slides.charts/ichartdatacell/formula/
---

## IChartDataCell.Formula property

Получает или задает формулу в стиле A1.

```csharp
public string Formula { get; set; }
```

### Примеры

```csharp
[C#]
IChartDataCell cell = workbook.GetCell(0, "B2");
cell.Formula = "1 + SUM(F2:H5)";
```

### См. также

* интерфейс [IChartDataCell](../../ichartdatacell)
* пространство имен [Aspose.Slides.Charts](../../ichartdatacell)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->