---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Skapar nya diagramserier och lägger till dem i samlingen.
type: docs
weight: 14
url: /sv/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) metod


Skapar en ny diagramserie och lägger till den i samlingen.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ av serie |

### Returvärde

Ny diagramserie.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metod


Skapar en ny diagramserie från [IChartDataCell](../../ichartdatacell/) och lägger till den i samlingen.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) som innehåller serienamn. |
| type | [ChartType](../../charttype/) | Typ som anger typ av serie |

### Returvärde

Tillagd diagramserie eller serie som redan finns i samlingen.

## Anmärkningar


Om en diagramserie skapas från samma cell som redan finns i samlingen lägger metoden till ingenting och returnerar dess index.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metod


Skapar en ny diagramserie från [IChartCellCollection](../../ichartcellcollection/) och lägger till den i samlingen.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Celler som innehåller serienamn. |
| type | [ChartType](../../charttype/) | Typ som anger typ av serie |

### Returvärde

Tillagd diagramserie eller serie som redan finns i samlingen.

## Anmärkningar


Om en diagramserie skapas från samma cell som redan finns i samlingen lägger metoden till ingenting och returnerar dess index.



## IChartSeriesCollection::Add(System::String, ChartType) metod


Skapar en ny diagramserie från värde och lägger till den i samlingen.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Serienamn. |
| type | [ChartType](../../charttype/) | Typ som anger typ av serie |

### Returvärde

Tillagd diagramserie.



## Se även

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartSeries](../../ichartseries/)
* Klass [IChartSeriesCollection](../)
* Klass [IChartDataCell](../../ichartdatacell/)
* Klass [IChartCellCollection](../../ichartcellcollection/)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)