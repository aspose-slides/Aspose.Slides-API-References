---
title: operator>=()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alltid false.
type: docs
weight: 183
url: /sv/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const metod


Returnerar alltid false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Returvärde

Alltid - false

## Nullable::operator>=(const T1\&) const metod


Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det specificerade objektet genom att tillämpa [operator>=()](./) på dessa värden.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av värdet att jämföra värdet som representeras av det aktuella objektet med |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | En konstant referens till ett objekt att jämföra det aktuella objektet med |

### Returvärde

Sant om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det specificerade objektet, annars - false

## Nullable::operator>=(const Nullable\<T1\>\&) const metod


Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det specificerade [Nullable](../)-objektet genom att tillämpa [operator>=()](./) på dessa värden.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
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

Sant om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det specificerade [Nullable](../)-objektet, annars - false

## Se också

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)