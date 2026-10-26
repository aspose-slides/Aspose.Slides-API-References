---
title: operator+()
second_title: Aspose.Slides pro C++ API Reference
description: Vrátí výchozí vytvořenou instanci třídy Nullable<T>.
type: docs
weight: 209
url: /cs/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const method

Vrátí výchozí vytvořenou instanci třídy Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const method

Sečte nullable a non-nullable hodnoty.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ pravého operandu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | hodnota k přidání. |

### Návratová hodnota

Výsledek sčítání.

## Nullable::operator+(const Nullable\<T1\>\&) const method

Sečte nullable hodnoty.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ pravého operandu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | hodnota k přidání. |

### Návratová hodnota

Výsledek sčítání.

## Viz také

* Třída [Nullable](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)