---
title: ChartDataWorksheetCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa la colección de hojas de cálculo del libro de datos de gráfico.
type: docs
weight: 1260
url: /es/net/aspose.slides.charts/chartdataworksheetcollection/
---
## ChartDataWorksheetCollection class

Representa la colección de hojas de cálculo del libro de datos de gráfico.

```csharp
public sealed class ChartDataWorksheetCollection : IChartDataWorksheetCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides.charts/chartdataworksheetcollection/count) { get; } | Devuelve el conteo. Solo lecturaInt32 . |
| [IsSynchronized](../../aspose.slides.charts/chartdataworksheetcollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lecturaBoolean . |
| [Item](../../aspose.slides.charts/chartdataworksheetcollection/item) { get; } | Devuelve la hoja de trabajo por index. |
| [SyncRoot](../../aspose.slides.charts/chartdataworksheetcollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lecturaObject . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CopyTo](../../aspose.slides.charts/chartdataworksheetcollection/copyto)(Array, int) | Copiar a la matriz especificada. |
| [GetEnumerator](../../aspose.slides.charts/chartdataworksheetcollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |

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

### Ver también

* interface [IChartDataWorksheetCollection](../ichartdataworksheetcollection)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->