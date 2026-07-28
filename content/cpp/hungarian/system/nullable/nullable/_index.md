---
title: Nullable()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy példányt, amely null értéket képvisel.
type: docs
weight: 1
url: /hu/system/nullable/nullable/
---
## Nullable::Nullable() konstruktor

Létrehoz egy példányt, amely null értéket képvisel.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) konstruktor

Létrehoz egy példányt, amely null értéket képvisel.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) konstruktor

Létrehoz egy [Nullable](../) osztály példányt, amely a megadott értéket (szükség esetén) az alap típusú T értékévé konvertálja.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A megadott érték típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T1\& | Az újonnan létrehozott [Nullable](../) objektum által képviselendő érték konstans referenciája |

## Nullable::Nullable(const Nullable\<T1\>\&) konstruktor

Létrehoz egy példányt, amely az adott [Nullable](../) objektum által képviselt értéket ábrázolja. A megadott nullable objektum egy más típusú értéket is képviselhet, mint a létrehozott példány alap típusa, ebben az esetben a képviselt érték T típusú értékké konvertálódik.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A megadott [Nullable](../) objektum által képviselt érték típusa |

## Lásd még

* Osztály [Nullable](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)