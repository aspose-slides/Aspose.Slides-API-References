---
title: operator==()
second_title: Aspose.Slides for C++ API referenciája
description: Meghatározza, hogy a jelenlegi objektum által képviselt érték null-e.
type: docs
weight: 118
url: /hu/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const metódus

Megállapítja, hogy a jelenlegi objektum által képviselt érték null-e.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### Visszatérési érték

True ha a jelenlegi objektum által képviselt érték null, egyébként - false

## Nullable::operator==(const T1\&) const metódus

Megállapítja, hogy a jelenlegi objektum által képviselt érték megegyezik-e a megadott értékkel.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Az összehasonlítandó érték típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | A konstans referencia az összehasonlítandó értékre |

### Visszatérési érték

True ha a jelenlegi objektum által képviselt érték megegyezik a megadott értékkel, egyébként - false

## Nullable::operator==(const Nullable\<T1\>\&) const metódus

Megállapítja, hogy a jelenlegi objektum által képviselt érték megegyezik-e a megadott [Nullable](../) objektum által képviselt értékkel.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A [Nullable](../) objektum alapvető típusa, amellyel összehasonlít |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A [Nullable](../) objektum konstans referenciája, amellyel összehasonlít |

### Visszatérési érték

True ha a jelenlegi objektum által képviselt érték megegyezik a megadott [Nullable](../) objektum által képviselt értékkel, egyébként - false

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)