---
title: operator!=()
second_title: Aspose.Slides for C++ API referencia
description: Megállapítja, hogy a jelenlegi objektum által képviselt érték nem null-e.
type: docs
weight: 144
url: /hu/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const metódus


Megállapítja, hogy a jelenlegi objektum által képviselt érték nem null-e.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### Visszatérési érték

True, ha a jelenlegi objektum által képviselt érték nem null, egyébként false

## Nullable::operator!=(const T1\&) const metódus


Megállapítja, hogy a jelenlegi objektum által képviselt érték nem egyenlő a megadott értékkel.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A hasonlítandó érték típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | A hasonlítandó értékre mutató konstans referencia |

### Visszatérési érték

True, ha a jelenlegi objektum által képviselt érték nem egyenlő a megadott értékkel, egyébként false

## Nullable::operator!=(const Nullable\<T1\>\&) const metódus


Megállapítja, hogy a jelenlegi objektum által képviselt érték nem egyenlő a megadott [Nullable](../) objektummal.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A [Nullable](../) objektum alapvető típusa, amellyel összehasonlítani kell |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A [Nullable](../) objektumra mutató konstans referencia, amellyel összehasonlítani kell |

### Visszatérési érték

True, ha a jelenlegi objektum által képviselt érték nem egyenlő a megadott [Nullable](../) objektummal, egyébként false

## Lásd még

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)