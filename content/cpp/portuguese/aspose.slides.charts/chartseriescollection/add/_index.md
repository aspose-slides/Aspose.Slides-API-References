---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova série de gráfico e a adiciona à coleção.
type: docs
weight: 53
url: /pt/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) método


Cria uma nova série de gráfico e a adiciona à coleção.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Tipo da série |

### Valor de retorno

Nova série de gráfico.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) método


Cria uma nova série de gráfico a partir de [ChartDataCell](../../chartdatacell/) e a adiciona à coleção.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) que contém o nome da série. |
| type | [ChartType](../../charttype/) | Tipo que define o tipo da série |

### Valor de retorno

Série de gráfico adicionada ou série que já está na coleção.

## Observações


Se a série de gráfico for criada a partir da mesma célula já presente na coleção, então o método não adiciona nada e devolve seu índice.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) método


Cria uma nova série de gráfico a partir de [ChartCellCollection](../../chartcellcollection/) e a adiciona à coleção.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Células que contêm o nome da série. |
| type | [ChartType](../../charttype/) | Tipo que define o tipo da série |

### Valor de retorno

Série de gráfico adicionada ou série que já está na coleção.

## Observações


Se a série de gráfico for criada a partir da mesma célula já presente na coleção, então o método não adiciona nada e devolve seu índice.



## ChartSeriesCollection::Add(System::String, ChartType) método


Cria uma nova série de gráfico a partir de um valor e a adiciona à coleção.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nome da série. |
| type | [ChartType](../../charttype/) | Tipo que define o tipo da série |

### Valor de retorno

Série de gráfico adicionada.



## Ver também

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [ChartSeriesCollection](../)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCellCollection](../../ichartcellcollection/)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)