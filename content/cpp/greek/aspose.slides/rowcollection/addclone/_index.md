---
title: AddClone()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.
type: docs
weight: 53
url: /el/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) method


Δημιουργεί ένα αντίγραφο της συγκεκριμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) που χρησιμοποιείται ως πρότυπο. |
| withAttachedRows | **bool** | True για την αντιγραφή επίσης όλων των γραμμών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

### Return Value

Πρόσθετες γραμμές.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IRow](../../irow/)
* Κλάση [RowCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)