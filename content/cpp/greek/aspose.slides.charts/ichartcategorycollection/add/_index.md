---
title: Add()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά, δημιουργεί νέα κατηγορία γραφήματος από IChartDataCell και την προσθέτει στη συλλογή.
type: docs
weight: 53
url: /el/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) μέθοδος


Αν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά, δημιουργεί νέα κατηγορία γραφήματος από [IChartDataCell](../../ichartdatacell/) και την προσθέτει στη συλλογή.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) χρησιμοποιείται για τη δημιουργία κατηγορίας γραφήματος. |

### Τιμή επιστροφής

Προστιθέμενη ή υπάρχουσα κατηγορία.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) μέθοδος


Δημιουργεί νέο [IChartCategory](../../ichartcategory/) από την τιμή και το προσθέτει στη συλλογή.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Η τιμή. |

### Τιμή επιστροφής

Προστιτέθηκε [IChartCategory](../../ichartcategory/).
## Παρατηρήσεις



Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε [IChartDataWorkbook](../../ichartdataworkbook/) για προσθήκη ή επεξεργασία τιμών κελιού, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να ξεπερνά το 16711680



## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartCategory](../../ichartcategory/)
* Κλάση [IChartDataCell](../../ichartdatacell/)
* Κλάση [IChartCategoryCollection](../)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)