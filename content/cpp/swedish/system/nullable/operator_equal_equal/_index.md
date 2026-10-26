---
title: operator==()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om värdet som representeras av det aktuella objektet är null.
type: docs
weight: 118
url: /sv/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const metod

Bestämmer om värdet som representeras av det aktuella objektet är null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### Returvärde

True om värdet som representeras av det aktuella objektet är null, annars - false

## Nullable::operator==(const T1\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet är lika med det angivna värdet.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
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

True om värdet som representeras av det aktuella objektet är lika med det angivna värdet, annars - false

## Nullable::operator==(const Nullable\<T1\>\&) const metod

Bestämmer om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](../)-objektet.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
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

True om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](../)-objektet, annars - false

## Se också

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)