---
title: AddClone()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.
type: docs
weight: 53
url: /el/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


Δημιουργεί ένα αντίγραφο της καθορισμένης γραμμής προτύπου και το εισάγει στο κάτω μέρος ενός πίνακα.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | **bool** | True για να αντιγράψετε επίσης όλες τις στήλες που είναι συνδεδεμένες με τη γραμμή προτύπου. |

### Τιμή Επιστροφής

Προστεθειμένες στήλες.

## Δείτε επίσης

* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IColumn](../../icolumn/)
* Κλάση [ColumnCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)