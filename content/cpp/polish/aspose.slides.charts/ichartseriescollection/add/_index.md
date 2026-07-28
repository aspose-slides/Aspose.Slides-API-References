---
title: Add()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nową serię wykresu i dodaje ją do kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) metoda


Tworzy nową serię wykresu i dodaje ją do kolekcji.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ serii |

### Wartość zwracana

Nowa seria wykresu.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metoda


Tworzy nową serię wykresu z [IChartDataCell](../../ichartdatacell/) i dodaje ją do kolekcji.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) które zawierają nazwę serii. |
| type | [ChartType](../../charttype/) | Ustawia typ serii |

### Wartość zwracana

Dodana seria wykresu lub seria, która już znajduje się w kolekcji.
## Uwagi


Jeśli seria wykresu została utworzona z tej samej komórki już znajdującej się w kolekcji, metoda nie dodaje nic i zwraca jej indeks.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metoda


Tworzy nową serię wykresu z [IChartCellCollection](../../ichartcellcollection/) i dodaje ją do kolekcji.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Komórki które zawierają nazwę serii. |
| type | [ChartType](../../charttype/) | Ustawia typ serii |

### Wartość zwracana

Dodana seria wykresu lub seria, która już znajduje się w kolekcji.
## Uwagi


Jeśli seria wykresu została utworzona z tej samej komórki już znajdującej się w kolekcji, metoda nie dodaje nic i zwraca jej indeks.



## IChartSeriesCollection::Add(System::String, ChartType) metoda


Tworzy nową serię wykresu z wartości i dodaje ją do kolekcji.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nazwa serii. |
| type | [ChartType](../../charttype/) | Ustawia typ serii |

### Wartość zwracana

Dodana seria wykresu.



## Zobacz również

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)