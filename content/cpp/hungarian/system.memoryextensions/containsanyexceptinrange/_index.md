---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides for C++ API-referencia
description: Ellenőrzi, hogy egy csak olvasható span tartalmaz-e olyan elemet, amely kívül esik a megadott tartományon.
type: docs
weight: 79
url: /hu/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény

Ellenőrzi, hogy egy csak olvasható span tartalmaz-e olyan elemet, amely kívül esik a megadott tartományon.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa (összehasonlíthatónak kell lennie) |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keres |
| lowInclusive | const T\& | Az alsó határ (inkluzív) |
| highInclusive | const T\& | A felső határ (inkluzív) |

### Visszatérési érték

true, ha a tartományon kívül eső elem található, false egyébként

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) függvény

Ellenőrzi, hogy egy módosítható span tartalmaz-e olyan elemet, amely kívül esik a megadott tartományon.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa (összehasonlíthatónak kell lennie) |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A módosítható span, amelyben keres |
| lowInclusive | const T\& | Az alsó határ (inkluzív) |
| highInclusive | const T\& | A felső határ (inkluzív) |

### Visszatérési érték

true, ha a tartományon kívül eső elem található, false egyébként

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)