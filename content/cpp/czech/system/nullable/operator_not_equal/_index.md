---
title: operator!=()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda hodnota reprezentovaná aktuálním objektem není nulová.
type: docs
weight: 144
url: /cs/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const method


Určuje, zda hodnota reprezentovaná aktuálním objektem není nulová.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### Návratová hodnota

True pokud hodnota reprezentovaná aktuálním objektem není nulová, jinak - false

## Nullable::operator!=(const T1\&) const method


Určuje, zda hodnota reprezentovaná aktuálním objektem není rovna zadané hodnotě.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ hodnoty, se kterou se má porovnávat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | Konstantní odkaz na hodnotu, se kterou se má porovnávat |

### Návratová hodnota

True pokud hodnota reprezentovaná aktuálním objektem není rovna zadané hodnotě, jinak - false

## Nullable::operator!=(const Nullable\<T1\>\&) const method


Určuje, zda hodnota reprezentovaná aktuálním objektem není rovna hodnotě reprezentované zadaným objektem [Nullable](../).

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Základní typ objektu [Nullable](../), se kterým se má porovnávat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Konstantní odkaz na objekt [Nullable](../), se kterým se má porovnávat |

### Návratová hodnota

True pokud hodnota reprezentovaná aktuálním objektem není rovna hodnotě reprezentované zadaným objektem [Nullable](../), jinak - false

## Viz také

* Třída [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)