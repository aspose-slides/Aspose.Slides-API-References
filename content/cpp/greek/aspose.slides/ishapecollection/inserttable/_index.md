---
title: InsertTable()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.
type: docs
weight: 443
url: /el/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) μέθοδος

Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη x του πίνακα, σε μονάδες σημείων. |
| y | **float** | Η συντεταγμένη y του πίνακα, σε μονάδες σημείων. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ένας πίνακας τύπου double που αντιπροσωπεύει τα πλάτη των στηλών του πίνακα\\u2019s, σε μονάδες σημείων. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ένας πίνακας τύπου double που αντιπροσωπεύει τα ύψη των γραμμών του πίνακα\\u2019s, σε μονάδες σημείων. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [ITable](../../itable/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ITable](../../itable/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)