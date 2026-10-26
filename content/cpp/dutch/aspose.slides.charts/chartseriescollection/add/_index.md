---
title: Add()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een nieuwe grafiekreeks aan en voegt deze toe aan de collectie.
type: docs
weight: 53
url: /nl/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) method


Maakt een nieuwe grafiekreeks aan en voegt deze toe aan de collectie.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Type van de reeks |

### Retourwaarde

Nieuwe grafiekreeks.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) method


Maakt een nieuwe grafiekreeks van [ChartDataCell](../../chartdatacell/) aan en voegt deze toe aan de collectie.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) die de naam van de reeks bevat. |
| type | [ChartType](../../charttype/) | Type van de reeks |

### Retourwaarde

Toegevoegde grafiekreeks of reeks die al in de collectie aanwezig is.
## Opmerkingen


Als een grafiekreeks afkomstig is van dezelfde cel die al in de collectie aanwezig is, voegt de methode niets toe en retourneert de index.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) method


Maakt een nieuwe grafiekreeks van [ChartCellCollection](../../chartcellcollection/) aan en voegt deze toe aan de collectie.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cellen die de naam van de reeks bevatten. |
| type | [ChartType](../../charttype/) | Type van de reeks |

### Retourwaarde

Toegevoegde grafiekreeks of reeks die al in de collectie aanwezig is.
## Opmerkingen


Als een grafiekreeks afkomstig is van dezelfde cel die al in de collectie aanwezig is, voegt de methode niets toe en retourneert de index.



## ChartSeriesCollection::Add(System::String, ChartType) method


Maakt een nieuwe grafiekreeks van de waarde aan en voegt deze toe aan de collectie.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Naam van de reeks. |
| type | [ChartType](../../charttype/) | Type van de reeks |

### Retourwaarde

Toegevoegde grafiekreeks.



## Zie ook

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeries](../../ichartseries/)
* Klasse [ChartSeriesCollection](../)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartCellCollection](../../ichartcellcollection/)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)