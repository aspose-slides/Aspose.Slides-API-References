---
title: operator!=()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om värdet som representeras av det aktuella objektet inte är null.
type: docs
weight: 144
url: /sv/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const metod

Bestämmer om värdet som representeras av det aktuella objektet inte är null.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### Returvärde

Sant om värdet som representeras av det aktuella objektet inte är null, annars - falskt

## Nullable::operator!=(const T1\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet inte är lika med det angivna värdet.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
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

Sant om värdet som representeras av det aktuella objektet inte är lika med det angivna värdet, annars - falskt

## Nullable::operator!=(const Nullable\<T1\>\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet inte är lika med värdet som representeras av det angivna [Nullable](../)-objektet.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
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

Sant om värdet som representeras av det aktuella objektet inte är lika med värdet som representeras av det angivna [Nullable](../)-objektet, annars - falskt

## Se även

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)