---
title: series_groups property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups propiedad
Obtiene los grupos de series.
            Solo lectura [`IChartSeriesGroupCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroupcollection).


### Observaciones

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en ejes primarios o en ejes secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupación de series es una agrupación por los grupos de tipos mencionados arriba y por el tipo de trazado primario/secundario.
            
2) Un grupo de series contiene algunas propiedades de series que son comunes para cada serie en el grupo ("propiedades del grupo de series"). "Propiedades del grupo de series" en la clase ChartSeriesGroup es lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

### Definición:
```python
@property
def series_groups(self):
    ...
```


### Ver también
* clase [`IChartData`](/slides/python-net/es/aspose.slides.charts/ichartdata)
* clase [`IChartSeriesGroupCollection`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroupcollection)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)