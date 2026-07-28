---
title: Add()
second_title: Aspose.Slides dla C++ API Referencja
description: Tworzy nową serię wykresu i dodaje ją do kolekcji.
type: docs
weight: 53
url: /pl/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) metoda


Tworzy nową serię wykresu i dodaje ją do kolekcji.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ serii |

### Wartość zwracana

Nowa seria wykresu.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metoda


Tworzy nową serię wykresu z [ChartDataCell](../../chartdatacell/) i dodaje ją do kolekcji.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) które zawierają nazwę serii. |
| type | [ChartType](../../charttype/) | Typ określa typ serii |

### Wartość zwracana

Dodana seria wykresu lub seria, która już znajduje się w kolekcji.

## Uwagi


Jeśli seria wykresu została utworzona z tej samej komórki, która już znajduje się w kolekcji, metoda nie dodaje nic i zwraca jej indeks.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metoda


Tworzy nową serię wykresu z [ChartCellCollection](../../chartcellcollection/) i dodaje ją do kolekcji.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Komórki, które zawierają nazwę serii. |
| type | [ChartType](../../charttype/) | Typ określa typ serii |

### Wartość zwracana

Dodana seria wykresu lub seria, która już znajduje się w kolekcji.

## Uwagi


Jeśli seria wykresu została utworzona z tej samej komórki, która już znajduje się w kolekcji, metoda nie dodaje nic i zwraca jej indeks.



## ChartSeriesCollection::Add(System::String, ChartType) metoda


Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nazwa serii. |
| type | [ChartType](../../charttype/) | Typ określa typ serii |

### Wartość zwracana

Dodana seria wykresu.



## Zobacz także

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartSeries](../../ichartseries/)
* Klasa [ChartSeriesCollection](../)
* Klasa [IChartDataCell](../../ichartdatacell/)
* Klasa [IChartCellCollection](../../ichartcellcollection/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)