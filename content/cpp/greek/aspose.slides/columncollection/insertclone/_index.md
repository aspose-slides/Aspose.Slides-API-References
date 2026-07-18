---
title: InsertClone()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το εισάγει στην καθορισμένη θέση σε έναν πίνακα.
type: docs
weight: 66
url: /el/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) μέθοδος

Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το εισάγει στην καθορισμένη θέση σε έναν πίνακα.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης μιας νέας στήλης. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | **bool** | Αληθές για να αντιγραφούν επίσης όλες οι στήλες συνδεδεμένες με τη στήλη προτύπου. |

### Τιμή επιστροφής

Στήλες που εισάχθηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IColumn](../../icolumn/)
* Κλάση [ColumnCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)