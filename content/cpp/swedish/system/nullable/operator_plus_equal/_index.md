---
title: operator+=()
second_title: Aspose.Slides för C++ API-referens
description: Återställer det aktuella objektet så att det representerar ett null-värde.
type: docs
weight: 235
url: /sv/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) metod


Återställer det aktuella objektet så att det representerar ett null-värde.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### Returvärde

En kopia av objektet

## Nullable::operator+=(const T1\&) metod


Tillämpar [operator+=()](./) på värdet som det aktuella objektet representerar med det angivna värdet som högra argumentet.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av värdet som används som högra argumentet för [operator+=()](./) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | En konstant referens till värdet som används som högra argumentet för [operator+=()](./) som tillämpas på värdet som det aktuella objektet representerar. |

### Returvärde

En referens till objektet

## Nullable::operator+=(const Nullable\<T1\>\&) metod


Tillämpar [operator+=()](./) på värdet som det aktuella objektet representerar med värdet som representeras av det angivna [Nullable](../)-objektet som högra argumentet.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av ett [Nullable](../)-objekt vars värde som representeras av används som högra argumentet för [operator+=()](./) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | En konstant referens till [Nullable](../)-objekt vars värde som representeras av används som högra argumentet för [operator+=()](./) som tillämpas på värdet som det aktuella objektet representerar. |

### Returvärde

En referens till objektet

## Se också

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)