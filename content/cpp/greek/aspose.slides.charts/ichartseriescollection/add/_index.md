---
title: Add()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή.
type: docs
weight: 14
url: /el/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) μέθοδος


Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Τύπος της σειράς |

### Τιμή Επιστροφής

Νέα σειρά γραφήματος.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) μέθοδος


Δημιουργεί νέα σειρά γραφήματος από [IChartDataCell](../../ichartdatacell/) και την προσθέτει στη συλλογή.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) που περιέχει το όνομα της σειράς. |
| type | [ChartType](../../charttype/) | Τύπος που ορίζει τον τύπο της σειράς |

### Τιμή Επιστροφής

Η προστιθέμενη σειρά γραφήματος ή η σειρά που υπάρχει ήδη στη συλλογή.

## Παρατηρήσεις


Αν η σειρά γραφήματος προέρχεται από το ίδιο κελί που υπάρχει ήδη στη συλλογή, η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) μέθοδος


Δημιουργεί νέα σειρά γραφήματος από [IChartCellCollection](../../ichartcellcollection/) και την προσθέτει στη συλλογή.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Κελιά που περιέχουν το όνομα της σειράς. |
| type | [ChartType](../../charttype/) | Τύπος που ορίζει τον τύπο της σειράς |

### Τιμή Επιστροφής

Η προστιθέμενη σειρά γραφήματος ή η σειρά που υπάρχει ήδη στη συλλογή.

## Παρατηρήσεις


Αν η σειρά γραφήματος προέρχεται από το ίδιο κελί που υπάρχει ήδη στη συλλογή, η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της.



## IChartSeriesCollection::Add(System::String, ChartType) μέθοδος


Δημιουργεί νέα σειρά γραφήματος από τιμή και την προσθέτει στη συλλογή.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Όνομα σειράς. |
| type | [ChartType](../../charttype/) | Τύπος που ορίζει τον τύπο της σειράς |

### Τιμή Επιστροφής

Η προστιθέμενη σειρά γραφήματος.



## Δείτε επίσης

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)