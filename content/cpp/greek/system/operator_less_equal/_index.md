---
title: operator<=()
second_title: Aspose.Slides για το API αναφορά C++
description: 
type: docs
weight: 2081
url: /el/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) function

Πάντα επιστρέφει ψευδές.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) function

Καθορίζει αν η καθορισμένη τιμή είναι μικρότερη ή ίση με την τιμή που εκπροσωπείται από το καθορισμένο αντικείμενο [Nullable](../nullable/) εφαρμόζοντας [operator<=()](./) σε αυτές τις τιμές.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | Ο τύπος της πρώτης τιμής σύγκρισης |
| T2 | Ο υποκείμενος τύπος του αντικειμένου [Nullable](../nullable/) που εκπροσωπεί τη δεύτερη τιμή σύγκρισης |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | Μια σταθερή αναφορά στην τιμή που θα χρησιμοποιηθεί ως η πρώτη τιμή σύγκρισης |
| other | const [Nullable](../nullable/)\<T2\>\& | Μια σταθερή αναφορά στο αντικείμενο [Nullable](../nullable/) της οποίας η εκπροσωπούμενη τιμή θα χρησιμοποιηθεί ως η δεύτερη τιμή σύγκρισης |

### Τιμή επιστροφής

Αληθές εάν η πρώτη τιμή σύγκρισης είναι μικρότερη ή ίση με τη δεύτερη τιμή σύγκρισης, διαφορετικά - ψευδές

## System::operator<=(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## Δείτε επίσης

* Κλάση [DateTime](../datetime/)
* Κλάση [DateTimeOffset](../datetimeoffset/)
* Κλάση [Nullable](../nullable/)
* Κλάση [TimeSpan](../timespan/)
* Δομή [IsNullable](../isnullable/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)