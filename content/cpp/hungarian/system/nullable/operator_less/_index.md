---
title: operator<()
second_title: Aspose.Slides C++ API Referenciája
description: Mindig hamis értéket ad vissza.
type: docs
weight: 170
url: /hu/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const metódus


Mindig hamis értéket ad vissza.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const metódus


Meghatározza, hogy az aktuális objektum által képviselt érték kisebb-e a megadott értéknél, a [operator<()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A hasonlítandó érték típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | A konstans referencia a hasonlítandó értékre |

### Visszatérési érték

Igaz, ha az aktuális objektum által képviselt érték kisebb a megadott értéknél, egyébként - hamis

## Nullable::operator<(const Nullable\<T1\>\&) const metódus


Meghatározza, hogy az aktuális objektum által képviselt érték kisebb-e a megadott [Nullable](../) objektum által képviselt értéknél, a [operator<()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A [Nullable](../) objektum alaptípusa a hasonlításhoz |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A konstans referenciája a [Nullable](../) objektumra a hasonlításhoz |

### Visszatérési érték

Igaz, ha az aktuális objektum által képviselt érték kisebb a megadott [Nullable](../) objektum által képviselt értéknél, egyébként - hamis

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)