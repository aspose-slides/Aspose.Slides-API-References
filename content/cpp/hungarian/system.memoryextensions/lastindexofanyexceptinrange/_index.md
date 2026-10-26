---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API Referencia
description: Megkeresi a megadott tartományon kívül lévő bármely elem utolsó előfordulását egy spanon belül.
type: docs
weight: 248
url: /hu/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény

Megkeresi a megadott tartományon kívül lévő bármely elem utolsó előfordulását egy spanon belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keres |
| lowInclusive | const T\& | A tartomány alsó határa (inkluzív) |
| highInclusive | const T\& | A tartomány felső határa (inkluzív) |

### Visszatérési érték

A tartományon kívül lévő utolsó elem nulláról induló indexe, vagy -1, ha nem található

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) függvény

Megkeresi a megadott tartományon kívül lévő bármely elem utolsó előfordulását egy módosítható spanon belül.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A span, amelyben keres |
| lowInclusive | const T\& | A tartomány alsó határa (inkluzív) |
| highInclusive | const T\& | A tartomány felső határa (inkluzív) |

### Visszatérési érték

A tartományon kívül lévő utolsó elem nulláról induló indexe, vagy -1, ha nem található

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)