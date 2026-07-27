---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova série de gráfico e a adiciona à coleção.
type: docs
weight: 14
url: /pt/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) método


Cria uma nova série de gráfico e a adiciona à coleção.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Tipo da série |

### Valor de Retorno

Nova série de gráfico.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) método


Cria uma nova série de gráfico a partir de [IChartDataCell](../../ichartdatacell/) e a adiciona à coleção.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) que contém o nome da série. |
| type | [ChartType](../../charttype/) | Tipo definido da série |

### Valor de Retorno

Série de gráfico adicionada ou série que já está na coleção.

## Observações


Se a série de gráfico for criada a partir da mesma célula já presente na coleção, então o método não adiciona nada e retorna seu índice.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) método


Cria uma nova série de gráfico a partir de [IChartCellCollection](../../ichartcellcollection/) e a adiciona à coleção.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Células que contêm o nome da série. |
| type | [ChartType](../../charttype/) | Tipo definido da série |

### Valor de Retorno

Série de gráfico adicionada ou série que já está na coleção.

## Observações


Se a série de gráfico for criada a partir da mesma célula já presente na coleção, então o método não adiciona nada e retorna seu índice.



## IChartSeriesCollection::Add(System::String, ChartType) método


Cria uma nova série de gráfico a partir de um valor e a adiciona à coleção.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nome da série. |
| type | [ChartType](../../charttype/) | Tipo definido da série |

### Valor de Retorno

Série de gráfico adicionada.



## Veja Também

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)