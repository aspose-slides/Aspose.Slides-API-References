---
title: SeriesGroups
second_title: Aspose.Slides para .NET Referencia de la API
description: Obtiene los grupos de series. Solo lectura IChartSeriesGroupCollectionaspose.slides/ichartseriesgroupcollection.
type: docs
weight: 70
url: /es/aspose.slides.charts/chartdata/seriesgroups/
---

## Propiedad ChartData.SeriesGroups

Obtiene los grupos de series. Solo lectura [`IChartSeriesGroupCollection`](../../ichartseriesgroupcollection).

```csharp
public IChartSeriesGroupCollection SeriesGroups { get; }
```

### Notas

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables están definidos y descritos con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan en los ejes primarios o en los ejes secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupación de series es una agrupación por los tipos de grupos mencionados anteriormente y por el tipo de trazado primario/secundario. 2) Un grupo de series contiene algunas propiedades de serie que son comunes para cada serie en el grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Ver También

* interfaz [IChartSeriesGroupCollection](../../ichartseriesgroupcollection)
* clase [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->