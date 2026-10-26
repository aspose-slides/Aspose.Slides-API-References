---
title: operator<()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 2094
url: /sv/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) funktion




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) funktion




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) funktion


Returnerar alltid falskt.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) funktion


Avgör om det angivna värdet är mindre än värdet som representeras av det angivna [Nullable](../nullable/)-objektet genom att tillämpa [operator<()](./) på dessa värden.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av det första jämförelsekandidatavärdet |
| T2 | Den underliggande typen av [Nullable](../nullable/)-objektet som representerar det andra jämförelsekandidatavärdet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| some | const T1\& | En konstant referens till värdet som ska användas som den första jämförelsekandidaten |
| other | const [Nullable](../nullable/)\<T2\>\& | En konstant referens till [Nullable](../nullable/)-objektet vars representerade värde ska användas som den andra jämförelsekandidaten |

### Returvärde

True om den första jämförelsekandidaten är mindre än den andra jämförelsekandidaten, annars - false

## System::operator<(std::nullptr_t, TimeSpan) funktion




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Se också

* Klass [DateTime](../datetime/)
* Klass [DateTimeOffset](../datetimeoffset/)
* Klass [Nullable](../nullable/)
* Klass [TimeSpan](../timespan/)
* Struktur [IsNullable](../isnullable/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)