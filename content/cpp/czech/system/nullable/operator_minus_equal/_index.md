---
title: operator-=()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací instanci třídy Nullable, která představuje nulovou hodnotu.
type: docs
weight: 248
url: /cs/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) metoda

Vrací instanci třídy [Nullable](../), která představuje nulovou hodnotu.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) metoda

Použije [operator-=()](./) na hodnotu reprezentovanou aktuálním objektem s použitím zadané hodnoty jako pravého argumentu.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ hodnoty použité jako pravá hodnota [operator-=()](./) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const T1\& | Konstantní reference na hodnotu, která je použita jako pravá hodnota [operator-=()](./) aplikovaná na hodnotu reprezentovanou aktuálním objektem. |

### Návratová hodnota

Odkaz na sebe

## Nullable::operator-=(const Nullable\<T1\>\&) metoda

Použije [operator-=()](./) na hodnotu reprezentovanou aktuálním objektem s hodnotou reprezentovanou specifikovaným objektem [Nullable](../) jako pravým argumentem.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Základní typ objektu [Nullable](../), jehož hodnota je použita jako pravý argument [operator-=()](./) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Konstantní reference na objekt [Nullable](../), jehož hodnota je použita jako pravý argument [operator-=()](./) aplikovaný na hodnotu reprezentovanou aktuálním objektem. |

### Návratová hodnota

Odkaz na sebe

## Viz také

* Třída [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)