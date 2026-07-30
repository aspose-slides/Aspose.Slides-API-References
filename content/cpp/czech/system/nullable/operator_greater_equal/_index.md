---
title: operator>=()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vždy vrací false.
type: docs
weight: 183
url: /cs/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const metoda


Vždy vrací false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Návratová hodnota

Vždy - false

## Nullable::operator>=(const T1\&) const metoda


Určuje, zda je hodnota reprezentovaná aktuálním objektem větší nebo rovna hodnotě reprezentované zadaným objektem aplikací [operator>=()](./) na tyto hodnoty.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Základní typ hodnoty, která se má porovnat s hodnotou reprezentovanou aktuálním objektem |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | Konstantní odkaz na objekt, se kterým se má porovnat aktuální objekt |

### Návratová hodnota

True, pokud je hodnota reprezentovaná aktuálním objektem větší nebo rovna hodnotě reprezentované zadaným objektem, jinak - false

## Nullable::operator>=(const Nullable\<T1\>\&) const metoda


Určuje, zda je hodnota reprezentovaná aktuálním objektem větší nebo rovna hodnotě reprezentované zadaným objektem [Nullable](../) aplikací [operator>=()](./) na tyto hodnoty.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Základní typ objektu [Nullable](../), se kterým se má porovnat |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Konstantní odkaz na objekt [Nullable](../), se kterým se má porovnat |

### Návratová hodnota

True, pokud je hodnota reprezentovaná aktuálním objektem větší nebo rovna hodnotě reprezentované zadaným objektem [Nullable](../), jinak - false

## Viz také

* Třída [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)