---
title: Worksheets
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene una colección de hojas de cálculo.
type: docs
weight: 10
url: /es/aspose.slides.charts/chartdataworkbook/worksheets/
---

## Propiedad ChartDataWorkbook.Worksheets

Obtiene una colección de hojas de cálculo.

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

* interfaz [IChartDataWorksheetCollection](../../ichartdataworksheetcollection)
* clase [ChartDataWorkbook](../../chartdataworkbook)
* espacio de nombres [Aspose.Slides.Charts](../../chartdataworkbook)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->