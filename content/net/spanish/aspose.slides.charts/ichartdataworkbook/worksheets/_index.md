---
title: Worksheets
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene una colección de hojas de trabajo.
type: docs
weight: 10
url: /es/aspose.slides.charts/ichartdataworkbook/worksheets/
---

## Propiedad IChartDataWorkbook.Worksheets

Obtiene una colección de hojas de trabajo.

```csharp
public IChartDataWorksheetCollection Worksheets { get; }
```

### Ejemplos

Ejemplo:

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

### Véase también

* interface [IChartDataWorksheetCollection](../../ichartdataworksheetcollection)
* interface [IChartDataWorkbook](../../ichartdataworkbook)
* namespace [Aspose.Slides.Charts](../../ichartdataworkbook)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
