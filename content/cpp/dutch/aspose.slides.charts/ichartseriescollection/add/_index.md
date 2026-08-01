---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt nieuwe grafiekreeks en voegt deze toe aan de collectie.
type: docs
weight: 14
url: /nl/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) methode

Maakt een nieuwe grafiekreeks en voegt deze toe aan de collectie.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Type van reeks |

### Retourwaarde

Nieuwe grafiekreeks.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) methode

Maakt een nieuwe grafiekreeks van [IChartDataCell](../../ichartdatacell/) en voegt deze toe aan de collectie.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) die seriesnaam bevat. |
| type | [ChartType](../../charttype/) | Stelt het type van de reeks in |

### Retourwaarde

Toegevoegde grafiekreeks of reeks die al in de collectie aanwezig is.

## Opmerkingen

Als een grafiekreeks al vanuit dezelfde cel in de collectie bestaat, voegt de methode niets toe en retourneert het zijn index.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) methode

Maakt een nieuwe grafiekreeks van [IChartCellCollection](../../ichartcellcollection/) en voegt deze toe aan de collectie.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cellen die seriesnaam bevatten. |
| type | [ChartType](../../charttype/) | Stelt het type van de reeks in |

### Retourwaarde

Toegevoegde grafiekreeks of reeks die al in de collectie aanwezig is.

## Opmerkingen

Als een grafiekreeks al vanuit dezelfde cel in de collectie bestaat, voegt de methode niets toe en retourneert het zijn index.

## IChartSeriesCollection::Add(System::String, ChartType) methode

Maakt een nieuwe grafiekreeks van een waarde en voegt deze toe aan de collectie.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Seriesnaam. |
| type | [ChartType](../../charttype/) | Stelt het type van de reeks in |

### Retourwaarde

Toegevoegde grafiekreeks.

## Zie ook

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartSeries](../../ichartseries/)
* Klasse [IChartSeriesCollection](../)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartCellCollection](../../ichartcellcollection/)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)