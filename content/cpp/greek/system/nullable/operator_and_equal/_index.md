---
title: operator&=()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εφαρμόζει operator&=() στην τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας την καθορισμένη τιμή ως όρισμα δεξιάς πλευράς.
type: docs
weight: 274
url: /el/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) μέθοδος

Applies [operator&=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Η παράμετρος προτύπου που κάνει το SFINAE να λειτουργεί. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | **bool** | Μια λογική τιμή που χρησιμοποιείται ως τιμή δεξιάς πλευράς του [operator&=()](./) που εφαρμόζεται στην τιμή που αντιπροσωπεύει το τρέχον αντικείμενο. |

### Τιμή επιστροφής

Μια αναφορά στον εαυτό.

## Δείτε επίσης

* Κλάση [Nullable](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)