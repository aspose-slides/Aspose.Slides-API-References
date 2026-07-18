---
title: operator+()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Επιστρέφει ένα προεπιλεγμένα κατασκευασμένο στιγμιότυπο της κλάσης Nullable<T>.
type: docs
weight: 209
url: /el/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const μέθοδος

Επιστρέφει ένα προεπιλεγμένα κατασκευασμένο στιγμιότυπο της κλάσης Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const μέθοδος

Προσθέτει nullable και non-nullable τιμές.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος δεξιού τελεστή. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const T1\& | τιμή προς προσθήκη. |

### Τιμή επιστροφής

Αποτέλεσμα πρόσθεσης.

## Nullable::operator+(const Nullable\<T1\>\&) const μέθοδος

Προσθέτει nullable τιμές.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Τύπος δεξιού τελεστή. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | τιμή προς προσθήκη. |

### Τιμή επιστροφής

Αποτέλεσμα πρόσθεσης.

## Δείτε επίσης

* Κλάση [Nullable](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)