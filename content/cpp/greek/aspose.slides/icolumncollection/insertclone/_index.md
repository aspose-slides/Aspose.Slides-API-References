---
title: InsertClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το τοποθετεί στη συγκεκριμένη θέση σε έναν πίνακα.
type: docs
weight: 27
url: /el/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) μέθοδος

Δημιουργεί ένα αντίγραφο της καθορισμένης στήλης προτύπου και το τοποθετεί στη συγκεκριμένη θέση σε έναν πίνακα.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας στήλης. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) που χρησιμοποιείται ως πρότυπο. |
| withAttachedColumns | **bool** | Αληθές για την αντιγραφή επίσης όλων των στηλών που είναι συνδεδεμένες με τη στήλη προτύπου. |

### Επιστρεφόμενη τιμή

Στήλες που εισήχθησαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IColumn](../../icolumn/)
* Κλάση [IColumnCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)