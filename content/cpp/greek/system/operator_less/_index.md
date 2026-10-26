---
title: operator<()
second_title: Αναφορά API Aspose.Slides για C++
description: 
type: docs
weight: 2068
url: /el/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) συνάρτηση




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) συνάρτηση




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) συνάρτηση


Πάντα επιστρέφει false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) συνάρτηση


Καθορίζει εάν η συγκεκριμένη τιμή είναι μικρότερη από την τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [Nullable](../nullable/) εφαρμόζοντας [operator<()](./) σε αυτές τις τιμές.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Ο τύπος της πρώτης τιμής συγκρίσιμης |
| T2 | Ο υποκείμενος τύπος του αντικειμένου [Nullable](../nullable/) που αντιπροσωπεύει τη δεύτερη τιμή συγκρίσιμη |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| some | const T1\& | Μια σταθερή αναφορά στην τιμή που θα χρησιμοποιηθεί ως η πρώτη συγκρίσιμη |
| other | const [Nullable](../nullable/)\<T2\>\& | Μια σταθερή αναφορά στο αντικείμενο [Nullable](../nullable/) του οποίου η αντιπροσωπευόμενη τιμή θα χρησιμοποιηθεί ως η δεύτερη συγκρίσιμη |

### Τιμή επιστροφής

Αληθές εάν η πρώτη συγκρίσιμη είναι μικρότερη από τη δεύτερη συγκρίσιμη, διαφορετικά - false

## System::operator<(std::nullptr_t, TimeSpan) συνάρτηση




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Δείτε επίσης

* Κλάση [DateTime](../datetime/)
* Κλάση [DateTimeOffset](../datetimeoffset/)
* Κλάση [Nullable](../nullable/)
* Κλάση [TimeSpan](../timespan/)
* Δομή [IsNullable](../isnullable/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)