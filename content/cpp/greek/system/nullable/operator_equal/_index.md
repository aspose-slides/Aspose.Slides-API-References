---
title: operator=()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει null στο τρέχον αντικείμενο.
type: docs
weight: 14
url: /el/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) μέθοδος


Ορίζει null στο τρέχον αντικείμενο.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### Τιμή επιστροφής

Ένα αντικείμενο [Nullable](../) που αντιπροσωπεύει τιμή null.

## Nullable::operator=(const T1\&) μέθοδος


Αντικαθιστά την τρέχουσα τιμή που αντιπροσωπεύει το αντικείμενο με την καθορισμένη.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| The | τύπος της νέας τιμής που θα αντιπροσωπεύεται από το τρέχον αντικείμενο |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const T1\& | Η νέα τιμή που θα αντιπροσωπευθεί από το τρέχον αντικείμενο |

### Τιμή επιστροφής

Αναφορά στον εαυτό

## Nullable::operator=(const Nullable\<T1\>\&) μέθοδος


Αντικαθιστά την τρέχουσα τιμή που αντιπροσωπεύει το αντικείμενο με την καθορισμένη.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| The | τύπος της νέας τιμής που θα αντιπροσωπεύεται από το τρέχον αντικείμενο |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Η νέα τιμή που θα αντιπροσωπευθεί από το τρέχον αντικείμενο |

### Τιμή επιστροφής

Αναφορά στον εαυτό

## Δείτε επίσης

* Κλάση [Nullable](../)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)