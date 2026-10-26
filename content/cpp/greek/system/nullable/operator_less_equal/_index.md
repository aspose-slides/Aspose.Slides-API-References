---
title: operator<=()
second_title: Aspose.Slides για C++ API Reference
description: Πάντα επιστρέφει false.
type: docs
weight: 196
url: /el/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const μέθοδος

Πάντα επιστρέφει false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const μέθοδος

Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μικρότερη ή ίση με τη συγκεκριμένη τιμή εφαρμόζοντας [operator<=()](./) σε αυτές τις τιμές.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Ο τύπος της τιμής για σύγκριση |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const T1\& | Μία σταθερή αναφορά στη τιμή για σύγκριση |

### Τιμή Επιστροφής

True εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μικρότερη ή ίση με τη συγκεκριμένη τιμή, διαφορετικά - false

## Nullable::operator<=(const Nullable\<T1\>\&) const μέθοδος

Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μικρότερη ή ίση με τη τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [Nullable](../) εφαρμόζοντας [operator<=()](./) σε αυτές τις τιμές.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Ο υποκείμενος τύπος του αντικειμένου [Nullable](../) για σύγκριση |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Μία σταθερή αναφορά στο αντικείμενο [Nullable](../) για σύγκριση |

### Τιμή Επιστροφής

True εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μικρότερη ή ίση με τη τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [Nullable](../), διαφορετικά - false

## Δείτε επίσης

* Κλάση [Nullable](../)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)