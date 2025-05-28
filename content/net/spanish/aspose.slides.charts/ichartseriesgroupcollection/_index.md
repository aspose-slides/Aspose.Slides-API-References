---
title: IChartSeriesGroupCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la colección de grupos de series combinables.
type: docs
weight: 1880
url: /es/aspose.slides.charts/ichartseriesgroupcollection/
---

## Interfaz IChartSeriesGroupCollection

Representa la colección de grupos de series combinables.

```csharp
public interface IChartSeriesGroupCollection : IGenericCollection<IChartSeriesGroup>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.slides.charts/ichartseriesgroupcollection/item) { get; } | Obtiene el grupo de series por serie. (2 indexadores) |

### Comentarios

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables están definidos y descritos con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se grafican ya sea en ejes primarios o en ejes secundarios (no ambos casos en un solo grupo). Así, el principio de agrupamiento de series es un agrupamiento por tipos de grupos mencionados anteriormente y por tipo de graficación primaria/secundaria. 2) Un grupo de series contiene algunas propiedades de serie que son comunes para cada serie en el grupo ("propiedades de grupo de series"). Las "propiedades de grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades de grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Véase también

* interfaz [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interfaz [IChartSeriesGroup](../ichartseriesgroup)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->