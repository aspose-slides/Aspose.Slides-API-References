---
title: Worksheets
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient une collection de feuilles de calcul.
type: docs
weight: 10
url: /fr/net/aspose.slides.charts/ichartdataworkbook/worksheets/
---
## IChartDataWorkbook.Worksheets property

Obtient une collection de feuilles de calcul.

```csharp
public IChartDataWorksheetCollection Worksheets { get; }
```

### Exemples

Exemple :

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

### Voir également

* interface [IChartDataWorksheetCollection](../../ichartdataworksheetcollection)
* interface [IChartDataWorkbook](../../ichartdataworkbook)
* espace de noms [Aspose.Slides.Charts](../../ichartdataworkbook)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->