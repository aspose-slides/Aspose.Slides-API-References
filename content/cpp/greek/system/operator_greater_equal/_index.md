---
title: operator>=()
second_title: Aspose.Slides για C++ API Αναφορά
description: 
type: docs
weight: 2107
url: /el/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) συνάρτηση




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) συνάρτηση




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) συνάρτηση


Πάντα επιστρέφει false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) συνάρτηση


Καθορίζει εάν η συγκεκριμένη τιμή είναι μεγαλύτερη ή ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [Nullable](../nullable/) εφαρμόζοντας [operator>=()](./) σε αυτές τις τιμές.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Ο τύπος της πρώτης συγκρίσιμης τιμής |
| T2 | Ο υποκείμενος τύπος του αντικειμένου [Nullable](../nullable/) που αντιπροσωπεύει τη δεύτερη συγκρίσιμη τιμή |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| some | const T1\& | Μία σταθερή αναφορά στην τιμή που θα χρησιμοποιηθεί ως η πρώτη συγκρίσιμη τιμή |
| other | const [Nullable](../nullable/)\<T2\>\& | Μία σταθερή αναφορά στο αντικείμενο [Nullable](../nullable/) της οποίας η αναπαριστώμενη τιμή θα χρησιμοποιηθεί ως η δεύτερη συγκρίσιμη τιμή |

### Τιμή Επιστροφής

True αν η πρώτη συγκρίσιμη τιμή είναι μεγαλύτερη ή ίση με τη δεύτερη συγκρίσιμη τιμή, διαφορετικά - false

```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## Δείτε επίσης

* Κλάση [DateTime](../datetime/)
* Κλάση [DateTimeOffset](../datetimeoffset/)
* Κλάση [Nullable](../nullable/)
* Κλάση [TimeSpan](../timespan/)
* Δομή [IsNullable](../isnullable/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)