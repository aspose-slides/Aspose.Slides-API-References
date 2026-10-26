---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει νέο κελί στη συλλογή.
type: docs
weight: 53
url: /el/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) μέθοδος

Προσθέτει νέο κελί στη συλλογή.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Νέο κελί προς προσθήκη. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) μέθοδος

Δημιουργεί [IChartDataCell](../../ichartdatacell/) από την καθορισμένη τιμή και το προσθέτει στη συλλογή.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Η τιμή. |

## Παρατηρήσεις

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με το όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε [IChartDataWorkbook](../../ichartdataworkbook/) για προσθήκη ή επεξεργασία τιμών [Cell](../../../aspose.slides/cell/), βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartDataCell](../../ichartdatacell/)
* Κλάση [IChartCellCollection](../)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)