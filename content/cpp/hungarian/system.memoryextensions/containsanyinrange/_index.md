---
title: ContainsAnyInRange()
second_title: Aspose.Slides for C++ API Referencia
description: Ellenőrzi, hogy egy csak olvasható span tartalmaz-e bármely elemet a megadott tartományon belül.
type: docs
weight: 92
url: /hu/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Ellenőrzi, hogy egy csak olvasható span tartalmaz-e bármely elemet a megadott tartományon belül.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa (összehasonlítható kell legyen) |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| lowInclusive | const T\& | Az alsó határ (záró) |
| highInclusive | const T\& | A felső határ (záró) |

### Visszatérési érték

igaz, ha a tartományon belül bármely elem megtalálható, egyébként hamis

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Ellenőrzi, hogy egy módosítható span tartalmaz-e bármely elemet a megadott tartományon belül.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa (összehasonlítható kell legyen) |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span, amelyben keres |
| lowInclusive | const T\& | Az alsó határ (záró) |
| highInclusive | const T\& | A felső határ (záró) |

### Visszatérési érték

igaz, ha a tartományon belül bármely elem megtalálható, egyébként hamis

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)