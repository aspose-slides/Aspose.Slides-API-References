---
title: get_SeriesGroup()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 222
url: /pt/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) método




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) método


Retorna o grupo de séries no índice especificado.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Observações


1) Cada grupo de séries contém séries com tipos combináveis. Os grupos de tipos de séries combináveis são definidos e descritos com a enumeração CombinableSeriesTypesGroup. Além disso, cada grupo de séries contém séries que são plotadas tanto em eixos primários quanto em eixos secundários (não ambos os casos em um mesmo grupo). Portanto, o princípio de agrupamento de séries é um agrupamento pelos tipos de grupo mencionados acima e pelo tipo de plotagem primário/secundário. 2) O grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo ("series group properties"). "Series group properties" na classe [ChartSeriesGroup](../../chartseriesgroup/) é leitura/gravação. Cada "series group properties" pode ter uma projeção somente leitura na classe [ChartSeries](../../chartseries/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroup](../../ichartseriesgroup/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)