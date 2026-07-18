---
title: Add()
second_title: Aspose.Slides για C++ αναφορά API
description: Προσθέτει νέο κελί στη συλλογή.
type: docs
weight: 53
url: /el/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) μέθοδος

Προσθέτει νέο κελί στη συλλογή.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | New cell to add. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) μέθοδος

Δημιουργεί [ChartDataCell](../../chartdatacell/) από την καθορισμένη τιμή και την προσθέτει στη συλλογή.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

## Παρατηρήσεις

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με το όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί. Εάν χρησιμοποιείτε [ChartDataWorkbook](../../chartdataworkbook/) για την προσθήκη ή επεξεργασία τιμών [Cell](../../../aspose.slides/cell/), βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας. Ο μέγιστος αριθμός τιμών που προστίθενται με χρήση αυτής της μεθόδου δεν πρέπει να υπερβαίνει το 16711680

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartDataCell](../../ichartdatacell/)
* Κλάση [ChartCellCollection](../)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)