---
title: InsertClone()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στη συγκεκριμένη θέση σε έναν πίνακα.
type: docs
weight: 27
url: /el/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) μέθοδος

Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στη συγκεκριμένη θέση σε έναν πίνακα.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Δείκτης μιας νέας γραμμής. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | **bool** | Αληθές για να αντιγραφούν επίσης όλες οι γραμμές που είναι συνημμένες στη γραμμή προτύπου. |

### Return Value

Εισαχθείσες γραμμές.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IRow](../../irow/)
* Κλάση [IRowCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)