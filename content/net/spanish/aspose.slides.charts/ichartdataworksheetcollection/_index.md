---
title: IChartDataWorksheetCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la colección de hojas de trabajo del libro de datos de gráficos.
type: docs
weight: 1800
url: /es/aspose.slides.charts/ichartdataworksheetcollection/
---

## Interfaz IChartDataWorksheetCollection

Representa la colección de hojas de trabajo del libro de datos de gráficos.

```csharp
public interface IChartDataWorksheetCollection : IGenericCollection<IChartDataWorksheet>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.slides.charts/ichartdataworksheetcollection/item) { get; } | Devuelve la hoja de trabajo por índice. |

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

### También Vea

* interfaz [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interfaz [IChartDataWorksheet](../ichartdataworksheet)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->