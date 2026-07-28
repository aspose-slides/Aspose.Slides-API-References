---
title: operator>=()
second_title: Aspose.Slides C++ API referencia
description: Mindig hamis értéket ad vissza.
type: docs
weight: 183
url: /hu/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(stdnullptr_t) const metódus


Mindig hamis értéket ad vissza.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### Visszatérési érték

Mindig - hamis

## Nullable::operator>=(const T1\&) const metódus


Megállapítja, hogy a jelenlegi objektum által képviselt érték nagyobb vagy egyenlő-e a megadott objektum által képviselt értékkel, a [operator>=()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A jelenlegi objektum által képviselt értékhez összehasonlítandó érték alapvető típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | Állandó referencia egy objektumra, amellyel a jelenlegi objektumot összehasonlítjuk |

### Visszatérési érték

Igaz, ha a jelenlegi objektum által képviselt érték nagyobb vagy egyenlő a megadott objektum által képviselt értékkel, egyébként - hamis

## Nullable::operator>=(const Nullable\<T1\>\&) const metódus


Megállapítja, hogy a jelenlegi objektum által képviselt érték nagyobb vagy egyenlő-e a megadott [Nullable](../) objektummal, a [operator>=()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A [Nullable](../) objektummal való összehasonlításhoz használt alapvető típus |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Állandó referencia a [Nullable](../) objektumra, amellyel összehasonlítjuk |

### Visszatérési érték

Igaz, ha a jelenlegi objektum által képviselt érték nagyobb vagy egyenlő a megadott [Nullable](../) objektummal, egyébként - hamis

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)