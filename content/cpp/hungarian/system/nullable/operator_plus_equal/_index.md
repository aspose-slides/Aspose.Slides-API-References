---
title: operator+=()
second_title: Aspose.Slides a C++ API Referenciája
description: Visszaállítja az aktuális objektumot, hogy egy null-értéket képviseljen.
type: docs
weight: 235
url: /hu/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) metódus

Visszaállítja az aktuális objektumot, hogy egy null-értéket képviseljen.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Visszatérési érték

Az objektum egy másolata

## Nullable::operator+=(const T1\&) metódus

Alkalmazza [operator+=()](./) a jelenlegi objektum által képviselt értékre a megadott értéket jobboldali argumentumként felhasználva.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A [operator+=()](./) jobboldali értékként használt érték típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | Egy állandó referencia az értékre, amely a [operator+=()](./) jobboldali értékeként szolgál, amelyet az aktuális objektum által képviselt értékre alkalmaznak. |

### Visszatérési érték

Az objektumra mutató referencia

## Nullable::operator+=(const Nullable\<T1\>\&) metódus

Alkalmazza [operator+=()](./) a jelenlegi objektum által képviselt értékre, a megadott [Nullable](../) objektum által képviselt értéket jobboldali argumentumként felhasználva.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Egy [Nullable](../) objektum alaptípusa, amelynek képviselt értéke a [operator+=()](./) jobboldali argumentumaként szolgál |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Egy állandó referencia egy [Nullable](../) objektumra, amelynek képviselt értéke a [operator+=()](./) jobboldali argumentumaként szolgál, amelyet az aktuális objektum által képviselt értékre alkalmaznak. |

### Visszatérési érték

Az objektumra mutató referencia

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)