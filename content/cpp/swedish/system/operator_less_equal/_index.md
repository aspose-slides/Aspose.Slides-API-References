---
title: operator<=()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 2107
url: /sv/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) funktion




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) funktion




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) funktion


Returnerar alltid falskt.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) funktion


Bestämmer om det angivna värdet är mindre än eller lika med värdet som representeras av det angivna [Nullable](../nullable/) objektet genom att tillämpa [operator<=()](./) på dessa värden.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av det första jämförelsevärdet |
| T2 | Den underliggande typen av [Nullable](../nullable/) objektet som representerar det andra jämförelsevärdet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| some | const T1\& | En konstant referens till värdet som ska användas som det första jämförelsevärdet |
| other | const [Nullable](../nullable/)\<T2\>\& | En konstant referens till [Nullable](../nullable/) objektet vars representerade värde ska användas som det andra jämförelsevärdet |

### Returvärde

Sant om det första jämförelsevärdet är mindre än eller lika med det andra jämförelsevärdet, annars - falskt

## System::operator<=(std::nullptr_t, TimeSpan) funktion




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## Se även

* Klass [DateTime](../datetime/)
* Klass [DateTimeOffset](../datetimeoffset/)
* Klass [Nullable](../nullable/)
* Klass [TimeSpan](../timespan/)
* Struktur [IsNullable](../isnullable/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)