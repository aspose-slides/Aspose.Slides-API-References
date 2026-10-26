---
title: IChartSeriesGroupCollection class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection clase

Representa la colección de grupos de series combinables.

El tipo IChartSeriesGroupCollection expone los siguientes miembros:

Obtiene el grupo de series por índice.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### Observaciones

1) Cada grupo de series contiene series con tipos combinables. Los grupos de 
            tipos de series combinables están definidos y descritos con el enum CombinableSeriesTypesGroup. 
            Además, cada grupo de series contiene series que se trazan ya sea 
            en ejes principales o en ejes secundarios (no ambos casos en un mismo grupo). 
            Por lo tanto, el principio de agrupación de series es agrupar por los tipos de grupos mencionados 
            anteriormente y por el tipo de trazado principal/secundario.
            
2) Un grupo de series contiene algunas propiedades de series que son comunes para 
            cada serie en el grupo ("propiedades del grupo de series"). 
            Las "propiedades del grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. 
            Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)