---
title: operator<()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vždy vrací false.
type: docs
weight: 170
url: /cs/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const metoda


Vždy vrací false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const metoda


Určuje, zda je hodnota reprezentovaná aktuálním objektem menší než určená hodnota použitím [operator<()](./) na tyto hodnoty.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
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

True pokud je hodnota reprezentovaná aktuálním objektem menší než určená hodnota, jinak - false

## Nullable::operator<(const Nullable\<T1\>\&) const metoda


Určuje, zda je hodnota reprezentovaná aktuálním objektem menší než hodnota reprezentovaná určeným objektem [Nullable](../) použitím [operator<()](./) na tyto hodnoty.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
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

True pokud je hodnota reprezentovaná aktuálním objektem menší než hodnota reprezentovaná určeným objektem [Nullable](../), jinak - false

## Viz také

* Třída [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)