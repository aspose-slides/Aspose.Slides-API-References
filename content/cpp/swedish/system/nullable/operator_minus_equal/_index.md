---
title: operator-=()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en instans av Nullable-klass som representerar ett nullvärde.
type: docs
weight: 248
url: /sv/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) metod

Returnerar en instans av [Nullable](../) klass som representerar ett nullvärde.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) metod

Tillämpar [operator-=()](./) på värdet som representeras av det aktuella objektet med det angivna värdet som argument på högra sidan.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typen av värdet som används som värde på högra sidan av [operator-=()](./) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | En konstant referens till värdet som används som värde på högra sidan av [operator-=()](./) som appliceras på värdet som representeras av det aktuella objektet. |

### Returvärde

En referens till sig själv

## Nullable::operator-=(const Nullable\<T1\>\&) metod

Tillämpar [operator-=()](./) på värdet som representeras av det aktuella objektet med värdet som representeras av det angivna [Nullable](../)-objektet som argument på högra sidan.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Den underliggande typen av ett [Nullable](../)-objekt vars värde används som argument på högra sidan av [operator-=()](./) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | En konstant referens till ett [Nullable](../)-objekt vars värde används som argument på högra sidan av [operator-=()](./) som appliceras på värdet som representeras av det aktuella objektet. |

### Returvärde

En referens till sig själv

## Se även

* Klass [Nullable](../)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)