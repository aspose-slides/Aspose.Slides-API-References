---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides для .NET API Справочник
description: Представляет коллекцию листов рабочей книги данных диаграммы.
type: docs
weight: 1800
url: /ru/aspose.slides.charts/ichartdataworksheetcollection/
---

## Интерфейс IChartDataWorksheetCollection

Представляет коллекцию листов рабочей книги данных диаграммы.

```csharp
public interface IChartDataWorksheetCollection : IGenericCollection<IChartDataWorksheet>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides.charts/ichartdataworksheetcollection/item) { get; } | Возвращает лист по индексу. |

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Pie, 50, 50, 400, 500);
    IChartDataWorkbook workbook =  chart.ChartData.ChartDataWorkbook;
    foreach (IChartDataWorksheet worksheet in workbook.Worksheets)
    {
        string worksheetName = worksheet.Name;
    }
}
```

### См. также

* интерфейс [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* интерфейс [IChartDataWorksheet](../ichartdataworksheet)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->