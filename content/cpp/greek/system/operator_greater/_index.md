---
title: operator>()
second_title: Αναφορά API Aspose.Slides για C++
description: 
type: docs
weight: 2094
url: /el/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) συνάρτηση




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) συνάρτηση




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) συνάρτηση


Πάντα επιστρέφει ψευδής.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) συνάρτηση


Καθορίζει εάν η καθορισμένη τιμή είναι μεγαλύτερη από την τιμή που αντιπροσωπεύεται από το καθορισμένο [Nullable](../nullable/) αντικείμενο εφαρμόζοντας [operator>()](./) σε αυτές τις τιμές.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Τιμή Επιστροφής

Αληθές εάν η πρώτη τιμή σύγκρισης είναι μεγαλύτερη από τη δεύτερη τιμή σύγκρισης, διαφορετικά - ψευδής

## System::operator>(std::nullptr_t, TimeSpan) συνάρτηση




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## Δείτε επίσης

* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)