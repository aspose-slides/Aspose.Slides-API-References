---
title: operator<=()
second_title: Aspose.Slides C++ API referencia
description: Mindig hamis értéket ad vissza.
type: docs
weight: 196
url: /hu/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const metódus

Mindig hamis értéket ad vissza.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const metódus

Megállapítja, hogy a jelenlegi objektum által képviselt érték kisebb vagy egyenlő-e a megadott értékkel, a [operator<=()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az érték típusa, amellyel össze kell hasonlítani |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | Az értékhez való állandó referenciát, amellyel összehasonlít |

### Visszatérési érték

Igaz, ha a jelenlegi objektum által képviselt érték kisebb vagy egyenlő a megadott értékkel, egyébként - hamis

## Nullable::operator<=(const Nullable\<T1\>\&) const metódus

Megállapítja, hogy a jelenlegi objektum által képviselt érték kisebb vagy egyenlő-e a megadott [Nullable](../) objektum által képviselt értékkel, a [operator<=()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A [Nullable](../) objektum alap típusa, amellyel összehasonlít |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Az [Nullable](../) objektumhoz tartozó állandó referenciát, amellyel összehasonlít |

### Visszatérési érték

Igaz, ha a jelenlegi objektum által képviselt érték kisebb vagy egyenlő a megadott [Nullable](../) objektum által képviselt értékkel, egyébként - hamis

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)