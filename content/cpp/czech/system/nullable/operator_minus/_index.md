---
title: operator-()
second_title: Aspose.Slides pro C++ API Reference
description: Odečítá nullable a hodnoty ukazující na null.
type: docs
weight: 222
url: /cs/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const metoda


Odečítá nullable a hodnoty ukazující na null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ pravého operandu, měl by být nullptr_t. |

### Návratová hodnota

Prázdný objekt [Nullable](../).

## Nullable::operator-(const T1\&) const metoda


Odečítá nullable a ne-nullovatelné hodnoty.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ pravého operandu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | hodnota k odečtení. |

### Návratová hodnota

Výsledek odečtení.

## Nullable::operator-(const Nullable\<T1\>\&) const metoda


Odečítá nullable hodnoty.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ pravého operandu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | hodnota k odečtení. |

### Návratová hodnota

Výsledek odečtení.

## Viz také

* Třída [Nullable](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)