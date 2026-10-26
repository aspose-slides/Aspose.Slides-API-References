---
title: operator>()
second_title: Aspose.Slides pro C++ API Reference
description: Vždy vrací false.
type: docs
weight: 157
url: /cs/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const metoda

Vždy vrací false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const metoda

Určuje, zda hodnota reprezentovaná aktuálním objektem je větší než zadaná hodnota použitím [operator>()](./) na těchto hodnotách.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ hodnoty, se kterou se má porovnávat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | Konstantní reference na hodnotu, se kterou se má porovnávat |

### Návratová hodnota

True pokud je hodnota reprezentovaná aktuálním objektem větší než zadaná hodnota, jinak - false

## Nullable::operator>(const Nullable\<T1\>\&) const metoda

Určuje, zda hodnota reprezentovaná aktuálním objektem je větší než hodnota reprezentovaná zadaným objektem [Nullable](../) použitím [operator>()](./) na těchto hodnotách.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Základní typ objektu [Nullable](../) pro porovnání |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Konstantní reference na objekt [Nullable](../) pro porovnání |

### Návratová hodnota

True pokud je hodnota reprezentovaná aktuálním objektem větší než hodnota reprezentovaná zadaným objektem [Nullable](../), jinak - false

## Viz také

* Třída [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)