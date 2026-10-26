---
title: Clear()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δεν υποστηρίζεται επειδή ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μόνο για ανάγνωση.
type: docs
weight: 53
url: /el/system/array/clear/
---
## Array::Clear() μέθοδος

Δεν υποστηρίζεται επειδή ο πίνακας που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μόνο για ανάγνωση.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) μέθοδος

Αντικαθιστά **count** τιμές που ξεκινούν από το ευρετήριο **startIndex** στον καθορισμένο πίνακα με προεπιλεγμένες τιμές.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Type | Type of elements in the target array |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Πίνακας-στόχος |
| startIndex | int | Ευρετήριο από το οποίο ξεκινάη η αντικατάσταση των στοιχείων |
| count | int | Ο αριθμός των στοιχείων που θα αντικατασταθούν |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Μέθοδος [Type](../../object/type/)
* Κλάση [Array](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)