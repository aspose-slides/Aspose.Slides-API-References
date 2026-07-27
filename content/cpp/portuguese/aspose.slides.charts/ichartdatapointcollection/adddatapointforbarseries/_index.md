---
title: AddDataPointForBarSeries()
second_title: Referência da API Aspose.Slides para C++
description: Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType seja um dos subtipos Column ou Bar (veja também ChartTypeCharacterizer.IsChartTypeColumn(ChartType) e ChartTypeCharacterizer.IsChartTypeBar(ChartType) método).
type: docs
weight: 196
url: /pt/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) método

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType seja um dos [Column](../../../aspose.slides/column/) ou subtipos de Bar (veja também [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) e [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) método).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valor do ponto de dados |

### Valor de retorno

Novo ponto de dados.

## IChartDataPointCollection::AddDataPointForBarSeries(double) método

Cria o novo ponto de dados e o adiciona ao final da coleção. Aplicável a séries cujo chartType seja um dos [Column](../../../aspose.slides/column/) ou subtipos de Bar (veja também [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) e [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) método).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **double** | Valor do ponto de dados |

### Valor de retorno

Novo ponto de dados.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)