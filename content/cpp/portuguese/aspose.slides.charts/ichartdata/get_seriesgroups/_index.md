---
title: get_SeriesGroups()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém os grupos de séries. Somente leitura IChartSeriesGroupCollection.
type: docs
weight: 27
url: /pt/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() method

Obtém os grupos de séries. Somente leitura [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Observações

1) Cada grupo de séries contém séries com tipos combináveis. Grupos de tipos de séries combináveis definidos e descritos com o enum CombinableSeriesTypesGroup. Também cada grupo de séries contém séries que são plotadas ou nos eixos principais ou nos eixos secundários (não ambos os casos em um mesmo grupo). Portanto, o princípio de agrupamento de séries é um agrupamento pelos grupos de tipos mencionados acima e pelo tipo de plotagem principal/secundário.

2) Um grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo (\"series group properties\"). \"Series group properties\" na classe [ChartSeriesGroup](../../chartseriesgroup/) é leitura/gravação. Cada \"series group properties\" pode ter uma projeção somente leitura na classe [ChartSeries](../../chartseries/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Classe [IChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)