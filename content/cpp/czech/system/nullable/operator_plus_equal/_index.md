---
title: operator+=()
second_title: Aspose.Slides pro C++ – reference API
description: Resetuje aktuální objekt tak, aby představoval null-hodnotu.
type: docs
weight: 235
url: /cs/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) metoda

Resetuje aktuální objekt tak, aby představoval null-hodnotu.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Návratová hodnota

Kopie objektu

## Nullable::operator+=(const T1\&) metoda

Použije [operator+=()](./) na hodnotu reprezentovanou aktuálním objektem s použitím zadané hodnoty jako pravého argumentu.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ hodnoty použitý jako pravá hodnota [operator+=()](./) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | Konstantní reference na hodnotu, která je použita jako pravá hodnota [operator+=()](./) aplikovaného na hodnotu reprezentovanou aktuálním objektem. |

### Návratová hodnota

Odkaz na objekt

## Nullable::operator+=(const Nullable\<T1\>\&) metoda

Použije [operator+=()](./) na hodnotu reprezentovanou aktuálním objektem s hodnotou reprezentovanou zadaným [Nullable](../) objektem jako pravým argumentem.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Základní typ objektu [Nullable](../), jehož hodnota je použita jako pravý argument [operator+=()](./) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Konstantní reference na objekt [Nullable](../), jehož hodnota je použita jako pravý argument [operator+=()](./) aplikovaného na hodnotu reprezentovanou aktuálním objektem. |

### Návratová hodnota

Odkaz na objekt

## Viz také

* Třída [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)