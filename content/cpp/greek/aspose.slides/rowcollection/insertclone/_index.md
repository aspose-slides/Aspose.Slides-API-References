---
title: InsertClone()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το τοποθετεί στη συγκεκριμένη θέση σε έναν πίνακα.
type: docs
weight: 66
url: /el/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) μέθοδος

Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το τοποθετεί στη συγκεκριμένη θέση σε έναν πίνακα.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης μιας νέας γραμμής. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | **bool** | True για αντιγραφή επίσης όλων των γραμμών που συνδέονται με τη γραμμή προτύπου. |

### Τιμή Επιστροφής

Εισαχθείσες γραμμές.

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IRow](../../irow/)
* Κλάση [RowCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)