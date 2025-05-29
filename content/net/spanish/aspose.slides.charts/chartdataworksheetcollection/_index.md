---
title: ChartDataWorksheetCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la colección de hojas de trabajo del libro de trabajo de datos de gráfico.
type: docs
weight: 1320
url: /es/aspose.slides.charts/chartdataworksheetcollection/
---

## Clase ChartDataWorksheetCollection

Representa la colección de hojas de trabajo del libro de trabajo de datos de gráfico.

```csharp
public sealed class ChartDataWorksheetCollection : IChartDataWorksheetCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides.charts/chartdataworksheetcollection/count) { get; } | Devuelve la cantidad. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides.charts/chartdataworksheetcollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides.charts/chartdataworksheetcollection/item) { get; } | Devuelve la hoja de trabajo por índice. |
| [SyncRoot](../../aspose.slides.charts/chartdataworksheetcollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CopyTo](../../aspose.slides.charts/chartdataworksheetcollection/copyto)(Array, int) | Copia al arreglo especificado. |
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

### Véase También

* interfaz [IChartDataWorksheetCollection](../ichartdataworksheetcollection)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->