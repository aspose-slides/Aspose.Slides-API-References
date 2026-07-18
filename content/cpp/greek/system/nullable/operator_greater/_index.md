---
title: operator>()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Πάντα επιστρέφει false.
type: docs
weight: 157
url: /el/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const μέθοδος

Πάντα επιστρέφει false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const μέθοδος

Καθορίζει αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μεγαλύτερη από την καθορισμένη τιμή εφαρμόζοντας [operator>()](./) σε αυτές τις τιμές.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Ο τύπος της τιμής για σύγκριση |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const T1\& | Μια σταθερή αναφορά στην τιμή για σύγκριση |

### Τιμή Επιστροφής

Αληθές εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μεγαλύτερη από την καθορισμένη τιμή, διαφορετικά - false

## Nullable::operator>(const Nullable\<T1\>\&) const μέθοδος

Καθορίζει αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μεγαλύτερη από την τιμή που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [Nullable](../) εφαρμόζοντας [operator>()](./) σε αυτές τις τιμές.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Ο βασικός τύπος του αντικειμένου [Nullable](../) για σύγκριση |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Μια σταθερή αναφορά στο αντικείμενο [Nullable](../) για σύγκριση |

### Τιμή Επιστροφής

Αληθές εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μεγαλύτερη από την τιμή που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [Nullable](../), διαφορετικά - false

## Δείτε επίσης

* Κλάση [Nullable](../)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)