---
title: Equals()
second_title: Aspose.Slides for C++ API hivatkozás
description: Megállapítja, hogy a jelenlegi objektum által képviselt érték megegyezik-e a megadott Nullable objektum által képviselt értékkel.
type: docs
weight: 131
url: /hu/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const metódus


Megállapítja, hogy a jelenlegi objektum által képviselt érték megegyezik-e a megadott [Nullable](../) objektum által képviselt értékkel.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A [Nullable](../) objektum alapvető típusa, amellyel összehasonlítandó |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | Az [Nullable](../) objektumhoz tartozó állandó referencia, amellyel összehasonlítandó |

### Visszatérési érték

Igaz, ha a jelenlegi objektum által képviselt érték megegyezik a megadott [Nullable](../) objektum által képviselt értékkel, egyébként - hamis

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)