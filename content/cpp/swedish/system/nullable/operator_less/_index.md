---
title: operator<()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alltid falskt.
type: docs
weight: 170
url: /sv/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const metod

Returnerar alltid falskt.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet är mindre än det angivna värdet genom att tillämpa [operator<()](./) på dessa värden.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av värdet att jämföra med |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | En konstant referens till värdet att jämföra med |

### Returvärde

Sant om värdet som representeras av det aktuella objektet är mindre än det angivna värdet, annars - falskt

## Nullable::operator<(const Nullable\<T1\>\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet är mindre än värdet som representeras av det angivna [Nullable](../)-objektet genom att tillämpa [operator<()](./) på dessa värden.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av [Nullable](../)-objektet att jämföra med |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | En konstant referens till [Nullable](../)-objektet att jämföra med |

### Returvärde

Sant om värdet som representeras av det aktuella objektet är mindre än värdet som representeras av det angivna [Nullable](../)-objektet, annars - falskt

## Se även

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)