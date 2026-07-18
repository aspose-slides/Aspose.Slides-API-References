---
title: GetName()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει το όνομα της σταθεράς enum που έχει την καθορισμένη τιμή.
type: docs
weight: 40
url: /el/system/enum/getname/
---
## Enum::GetName(T) μέθοδος


Επιστρέφει το όνομα της σταθεράς enum που έχει την καθορισμένη τιμή.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T | Η τιμή της σταθεράς enum της οποίας η ονομασία πρέπει να επιστραφεί |

### Τιμή Επιστροφής

Το όνομα της συγκεκριμένης σταθεράς enum

## Δείτε επίσης

* Τύπος [UnderlyingType](../underlyingtype/)
* Κλάση [String](../../string/)
* Δομή [Enum](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)