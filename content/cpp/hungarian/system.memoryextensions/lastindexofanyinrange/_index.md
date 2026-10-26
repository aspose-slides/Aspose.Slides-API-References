---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides C++ API Referencia
description: Megkeresi a megadott tartományban bármely elem utolsó előfordulását egy spanben.
type: docs
weight: 261
url: /hu/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény


Megkeresi a megadott tartományban bármely elem utolsó előfordulását egy spanben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| lowInclusive | const T\& | A tartomány alsó határa (zárt) |
| highInclusive | const T\& | A tartomány felső határa (zárt) |

### Visszatérési érték

A tartományban lévő utolsó elem nulla alapú indexe, vagy -1, ha nem található

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) függvény


Megkeresi a megadott tartományban bármely elem utolsó előfordulását egy módosítható spanben.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A keresendő span |
| lowInclusive | const T\& | A tartomány alsó határa (zárt) |
| highInclusive | const T\& | A tartomány felső határa (zárt) |

### Visszatérési érték

A tartományban lévő utolsó elem nulla alapú indexe, vagy -1, ha nem található

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)