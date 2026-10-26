---
title: operator>()
second_title: Aspose.Slides for C++ API-referencia
description: Mindig hamis értéket ad vissza.
type: docs
weight: 157
url: /hu/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const metódus

Mindig false értéket ad vissza.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const metódus

Megállapítja, hogy a jelenlegi objektum által képviselt érték nagyobb-e a megadott értéknél, a [operator>()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | Az összehasonlítandó érték típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Az összehasonlítandó érték konstans referenciája |

### Visszatérési érték

True, ha a jelenlegi objektum által képviselt érték nagyobb a megadott értéknél, egyébként – false

## Nullable::operator>(const Nullable\<T1\>\&) const metódus

Megállapítja, hogy a jelenlegi objektum által képviselt érték nagyobb-e a megadott [Nullable](../) objektum által képviselt értéknél, a [operator>()](./) alkalmazásával ezekre az értékekre.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T1 | A [Nullable](../) objektum alapvető típusa, amellyel összehasonlítja |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A [Nullable](../) objektum konstans referenciája, amellyel összehasonlítja |

### Visszatérési érték

True, ha a jelenlegi objektum által képviselt érték nagyobb a megadott [Nullable](../) objektum által képviselt értéknél, egyébként – false

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)