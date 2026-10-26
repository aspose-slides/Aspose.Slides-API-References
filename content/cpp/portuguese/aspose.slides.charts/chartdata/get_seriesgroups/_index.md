---
title: get_SeriesGroups()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os grupos de séries. Somente leitura IChartSeriesGroupCollection.
type: docs
weight: 27
url: /pt/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() método

Obtém os grupos de séries. Somente leitura [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Observações

1) Cada grupo de séries contém séries com tipos combináveis. Os grupos de tipos de séries combináveis são definidos e descritos com o enum CombinableSeriesTypesGroup. Também cada grupo de séries contém séries que são plotadas tanto nos eixos primários quanto nos eixos secundários (não ambos os casos em um mesmo grupo). Assim, o princípio do agrupamento de séries é um agrupamento pelos grupos de tipos mencionados acima e pelo tipo de plotagem primário/secundário.

2) Grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo ("series group properties"). "Series group properties" na classe [ChartSeriesGroup](../../chartseriesgroup/) é leitura/gravação. Cada uma das "series group properties" pode ter uma projeção somente leitura na classe [ChartSeries](../../chartseries/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Classe [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)