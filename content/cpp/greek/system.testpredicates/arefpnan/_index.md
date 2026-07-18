---
title: AreFPNaN()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λεπτομέρειες χώρου ονομάτων
type: docs
weight: 1
url: /el/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) συνάρτηση

namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Πρώτος τύπος κινητής υποδιαστολής. |
| T2 | Δεύτερος τύπος κινητής υποδιαστολής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | T1 | Πρώτη τιμή κινητής υποδιαστολής. |
| rhs | T2 | Δεύτερη τιμή κινητής υποδιαστολής. |

### Τιμή επιστροφής

Αληθές αν και τα **lhs** και **rhs** είναι τιμές κινητής υποδιαστολής, ψευδές διαφορετικά.

## Παρατηρήσεις

Ελέγχει ότι δύο τιμές κινητής υποδιαστολής είναι και οι δύο NaN. Διαχειρίζεται την περίπτωση όταν υποστηρίζεται NaN χωρίς σήμανση.

## System::TestPredicates::AreFPNaN(T1, T2) συνάρτηση

Ελέγχει ότι δύο τιμές κινητής υποδιαστολής είναι και οι δύο NaN. Διαχειρίζεται την περίπτωση όταν το NaN χωρίς σήμανση δεν υποστηρίζεται.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Πρώτος τύπος κινητής υποδιαστολής. |
| T2 | Δεύτερος τύπος κινητής υποδιαστολής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lhs | T1 | Πρώτη τιμή κινητής υποδιαστολής. |
| rhs | T2 | Δεύτερη τιμή κινητής υποδιαστολής. |

### Τιμή επιστροφής

Επιστρέφει πάντα ψευδής επειδή η τιμή NaN δεν υποστηρίζεται.

## Δείτε επίσης

* Χώρος ονομάτων [System::TestPredicates](../)
* Βιβλιοθήκη [Aspose.Slides](../../)