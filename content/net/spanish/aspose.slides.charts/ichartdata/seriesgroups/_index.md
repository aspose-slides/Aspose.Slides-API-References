---
title: SeriesGroups
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene los grupos de series. Solo lectura IChartSeriesGroupCollectionaspose.slides.charts/ichartseriesgroupcollection.
type: docs
weight: 70
url: /es/aspose.slides.charts/ichartdata/seriesgroups/
---

## IChartData.SeriesGroups propiedad

Obtiene los grupos de series. Solo lectura [`IChartSeriesGroupCollection`](../../ichartseriesgroupcollection).

```csharp
public IChartSeriesGroupCollection SeriesGroups { get; }
```

### Comentarios

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enumerador CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en ejes primarios o en ejes secundarios (no ambos casos en un solo grupo). Así, el principio de agrupación de series es una agrupación por los grupos de tipos mencionados anteriormente y por el tipo de trazado primario/secundario. 2) Un grupo de series contiene ciertas propiedades de series que son comunes a cada serie en el grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Véase también

* interfaz [IChartSeriesGroupCollection](../../ichartseriesgroupcollection)
* interfaz [IChartData](../../ichartdata)
* espacio de nombres [Aspose.Slides.Charts](../../ichartdata)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->