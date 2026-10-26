---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny diagramserie och lägger till den i samlingen.
type: docs
weight: 53
url: /sv/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) metod


Skapar en ny diagramserie och lägger till den i samlingen.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ av serie |

### Returvärde

Ny diagramserie.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metod


Skapar en ny diagramserie från [ChartDataCell](../../chartdatacell/) och lägger till den i samlingen.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) som innehåller serienamn. |
| type | [ChartType](../../charttype/) | Typ av serie |

### Returvärde

Tillagd diagramserie eller en serie som redan finns i samlingen.
## Anmärkningar


Om en diagramserie har skapats från samma cell som redan finns i samlingen så lägger metoden till inget och returnerar dess index.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metod


Skapar en ny diagramserie från [ChartCellCollection](../../chartcellcollection/) och lägger till den i samlingen.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Celler som innehåller serienamn. |
| type | [ChartType](../../charttype/) | Typ av serie |

### Returvärde

Tillagd diagramserie eller en serie som redan finns i samlingen.
## Anmärkningar


Om en diagramserie har skapats från samma cell som redan finns i samlingen så lägger metoden till inget och returnerar dess index.



## ChartSeriesCollection::Add(System::String, ChartType) metod


Skapar en ny diagramserie från värde och lägger till den i samlingen.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Serienamn. |
| type | [ChartType](../../charttype/) | Typ av serie |

### Returvärde

Tillagd diagramserie.



## Se även

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)