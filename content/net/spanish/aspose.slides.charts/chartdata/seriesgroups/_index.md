---
title: SeriesGroups
second_title: Referencia de API de Aspose.Slides para .NET
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

### Observaciones

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enumerador CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en ejes primarios o en ejes secundarios (no en ambos casos en un mismo grupo). Por lo tanto, el principio de agrupación de series es una agrupación por los tipos de grupos mencionados anteriormente y por el tipo de trazado primario/secundario. 2) Un grupo de series contiene algunas propiedades de serie que son comunes para cada serie en el grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Vea También

* interfaz [IChartSeriesGroupCollection](../../ichartseriesgroupcollection)
* clase [ChartData](../../chartdata)
* espacio de nombres [Aspose.Slides.Charts](../../chartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->