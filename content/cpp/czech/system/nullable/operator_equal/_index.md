---
title: operator=()
second_title: Aspose.Slides pro C++ API Reference
description: Přiřadí null aktuálnímu objektu.
type: docs
weight: 14
url: /cs/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) metoda


Přiřadí null aktuálnímu objektu.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### Návratová hodnota

Objekt [Nullable](../) představující null-hodnotu.

## Nullable::operator=(const T1\&) metoda


Nahradí aktuálně reprezentovanou hodnotu objektu specifikovanou hodnotou.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| The | typ nové hodnoty, která má být reprezentována aktuálním objektem |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T1\& | Nová hodnota, která má být reprezentována aktuálním objektem |

### Návratová hodnota

Odkaz na sebe

## Nullable::operator=(const Nullable\<T1\>\&) metoda


Nahradí aktuálně reprezentovanou hodnotu objektu specifikovanou hodnotou.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| The | typ nové hodnoty, která má být reprezentována aktuálním objektem |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Nová hodnota, která má být reprezentována aktuálním objektem |

### Návratová hodnota

Odkaz na sebe

## Viz také

* Třída [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)