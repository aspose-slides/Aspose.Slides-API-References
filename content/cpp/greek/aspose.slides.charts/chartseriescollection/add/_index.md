---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί νέα σειρά διαγράμματος και την προσθέτει στη συλλογή.
type: docs
weight: 53
url: /el/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) μέθοδος


Δημιουργεί νέα σειρά διαγράμματος και την προσθέτει στη συλλογή.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Τύπος της σειράς |

### Τιμή Επιστροφής

Νέα σειρά διαγράμματος.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) μέθοδος


Δημιουργεί νέα σειρά διαγράμματος από [ChartDataCell](../../chartdatacell/) και την προσθέτει στη συλλογή.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) που περιέχει το όνομα της σειράς. |
| type | [ChartType](../../charttype/) | Ο τύπος θέτει τον τύπο της σειράς |

### Τιμή Επιστροφής

Προστιθέμενη σειρά διαγράμματος ή σειρά που υπάρχει ήδη στη συλλογή.

## Σχόλια


Εάν η σειρά διαγράμματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) μέθοδος


Δημιουργεί νέα σειρά διαγράμματος από [ChartCellCollection](../../chartcellcollection/) και την προσθέτει στη συλλογή.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Κελιά που περιέχουν το όνομα της σειράς. |
| type | [ChartType](../../charttype/) | Ο τύπος θέτει τον τύπο της σειράς |

### Τιμή Επιστροφής

Προστιθέμενη σειρά διαγράμματος ή σειρά που υπάρχει ήδη στη συλλογή.

## Σχόλια


Εάν η σειρά διαγράμματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της.



## ChartSeriesCollection::Add(System::String, ChartType) μέθοδος


Δημιουργεί νέα σειρά διαγράμματος από τιμή και την προσθέτει στη συλλογή.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Όνομα σειράς. |
| type | [ChartType](../../charttype/) | Ο τύπος θέτει τον τύπο της σειράς |

### Τιμή Επιστροφής

Προστιθέμενη σειρά διαγράμματος.



## Δείτε επίσης

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)