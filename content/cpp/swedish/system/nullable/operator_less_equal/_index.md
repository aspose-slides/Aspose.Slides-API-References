---
title: operator<=()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alltid false.
type: docs
weight: 196
url: /sv/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const metod

Returnerar alltid false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet är mindre än eller lika med det angivna värdet genom att tillämpa [operator<=()](./) på dessa värden.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
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

True if the value represented by the current object is less or equal to the specified value, otherwise - false

## Nullable::operator<=(const Nullable\<T1\>\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet är mindre än eller lika med värdet som representeras av det angivna [Nullable](../)-objektet genom att tillämpa [operator<=()](./) på dessa värden.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
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

True if the value represented by the current object is less or equal to the value represented by the specified [Nullable](../) object, otherwise - false

## Se även

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)