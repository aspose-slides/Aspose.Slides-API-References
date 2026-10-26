---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det specificerade Nullable-objektet.
type: docs
weight: 131
url: /sv/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const metod


Bestämmer om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det specificerade [Nullable](../)-objektet.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av [Nullable](../)-objektet att jämföra med |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | En konstant referens till [Nullable](../)-objektet att jämföra med |

### Returvärde

Sant om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det specificerade [Nullable](../)-objektet, annars - falskt

## Se även

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)