---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εάν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία γραφήματος από IChartDataCell και την προσθέτει στη συλλογή.
type: docs
weight: 92
url: /el/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) μέθοδος


Αν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία γραφήματος από το [IChartDataCell](../../ichartdatacell/) και την προσθέτει στη συλλογή.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) που χρησιμοποιείται για τη δημιουργία κατηγορίας γραφήματος. |

### Τιμή Επιστροφής

Προστεθείσα ή υπάρχουσα κατηγορία.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) μέθοδος


Δημιουργεί νέο [ChartCategory](../../chartcategory/) από την τιμή και το προσθέτει στη συλλογή.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Η τιμή. |

### Τιμή Επιστροφής

Προστέθηκε [IChartCategory](../../ichartcategory/).
## Σχόλια



Αυτή η μέθοδος προσθέτει φύλλο εργασίας με το όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε το [ChartDataWorkbook](../../chartdataworkbook/) για να προσθέσετε ή να επεξεργαστείτε τιμές κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680



## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartCategory](../../ichartcategory/)
* Κλάση [IChartDataCell](../../ichartdatacell/)
* Κλάση [ChartCategoryCollection](../)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)