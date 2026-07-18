---
title: operator-()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αφαιρεί nullable και τιμές με δείκτη null.
type: docs
weight: 222
url: /el/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const μέθοδος

Αφαιρεί nullable και τιμές με δείκτη null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Παραμέτρους προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος δεξιού τελεστή, πρέπει να είναι nullptr_t. |

### Τιμή επιστροφής

Κενό [Nullable](../) αντικείμενο.

## Nullable::operator-(const T1\&) const μέθοδος

Αφαιρεί nullable και non-nullable τιμές.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Παραμέτρους προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος δεξιού τελεστή. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const T1\& | τιμή προς αφαίρεση. |

### Τιμή επιστροφής

Αποτέλεσμα αφαίρεσης.

## Nullable::operator-(const Nullable\<T1\>\&) const μέθοδος

Αφαιρεί nullable τιμές.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Παραμέτρους προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος δεξιού τελεστή. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | τιμή προς αφαίρεση. |

### Τιμή επιστροφής

Αποτέλεσμα αφαίρεσης.

## Δείτε επίσης

* Κλάση [Nullable](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)