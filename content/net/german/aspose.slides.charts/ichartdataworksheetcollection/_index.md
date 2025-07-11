---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides für .NET API Referenz
description: Stellt die Sammlung von Arbeitsblättern des Diagrammdatenarbeitsbuchs dar.
type: docs
weight: 1800
url: /de/aspose.slides.charts/ichartdataworksheetcollection/
---

## IChartDataWorksheetCollection-Schnittstelle

Stellt die Sammlung von Arbeitsblättern des Diagrammdatenarbeitsbuchs dar.

```csharp
public interface IChartDataWorksheetCollection : IGenericCollection<IChartDataWorksheet>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.slides.charts/ichartdataworksheetcollection/item) { get; } | Gibt das Arbeitsblatt anhand des Index zurück. |

### Beispiele

Beispiel:

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

### Siehe auch

* Schnittstelle [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* Schnittstelle [IChartDataWorksheet](../ichartdataworksheet)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->