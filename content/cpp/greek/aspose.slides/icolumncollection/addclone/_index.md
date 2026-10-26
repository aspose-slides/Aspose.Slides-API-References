---
title: AddClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.
type: docs
weight: 14
url: /el/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) μέθοδος

Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | **bool** | True για αντιγραφή επίσης όλων των στηλών που είναι συνδεδεμένες με τη γραμμή προτύπου. |

### Τιμή επιστροφής

Στήλες που προστέθηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IColumn](../../icolumn/)
* Κλάση [IColumnCollection](../)
* Διάστημα ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)