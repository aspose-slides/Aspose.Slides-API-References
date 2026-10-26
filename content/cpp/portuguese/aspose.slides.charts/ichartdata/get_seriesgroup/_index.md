---
title: get_SeriesGroup()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 222
url: /pt/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) método




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) método


Retorna o grupo de séries no índice especificado.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Observações


1) Cada grupo de séries contém séries com tipos combináveis. Grupos de tipos de séries combináveis são definidos e descritos com o enum CombinableSeriesTypesGroup. Também cada grupo de séries contém séries que são plotadas tanto nos eixos primários quanto nos eixos secundários (não ambos os casos em um mesmo grupo). Portanto, o princípio do agrupamento de séries é um agrupamento pelos tipos de grupo mencionados acima e pelo tipo de plotagem primário/secundário. 2) O grupo de séries contém algumas propriedades de série que são comuns a cada série no grupo (\"propriedades do grupo de séries\"). \"Propriedades do grupo de séries\" na classe [ChartSeriesGroup](../../chartseriesgroup/) é leitura/gravação. Cada uma das \"propriedades do grupo de séries\" pode ter uma projeção somente leitura na classe [ChartSeries](../../chartseries/). 
## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroup](../../ichartseriesgroup/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)