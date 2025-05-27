---
title: Feuilles de calcul
second_title: Référence API Aspose.Slides pour .NET
description: Obtient une collection de feuilles de calcul.
type: docs
weight: 10
url: /fr/aspose.slides.charts/ichartdataworkbook/worksheets/
---

## Propriété IChartDataWorkbook.Worksheets

Obtient une collection de feuilles de calcul.

```csharp
public IChartDataWorksheetCollection Worksheets { get; }
```

### Exemples

Exemple:

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

### Voir Aussi

* interface [IChartDataWorksheetCollection](../../ichartdataworksheetcollection)
* interface [IChartDataWorkbook](../../ichartdataworkbook)
* namespace [Aspose.Slides.Charts](../../ichartdataworkbook)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->
