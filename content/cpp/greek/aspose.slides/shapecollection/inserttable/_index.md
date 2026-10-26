---
title: InsertTable()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.
type: docs
weight: 482
url: /el/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) μέθοδος

Δημιουργεί ένα νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στη θέση που θα εισαχθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη x του πίνακα, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πίνακα, σε σημεία. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ένας πίνακας τύπου double που αντιπροσωπεύει τα πλάτη των στηλών του πίνακα, σε σημεία. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ένας πίνακας τύπου double που αντιπροσωπεύει τα ύψη των γραμμών του πίνακα, σε σημεία. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [ITable](../../itable/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ITable](../../itable/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)