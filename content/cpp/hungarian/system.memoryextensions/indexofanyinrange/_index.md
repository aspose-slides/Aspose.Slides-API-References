---
title: IndexOfAnyInRange()
second_title: Aspose.Slides C++ API Referenciája
description: Megkeresi az első elem indexét, amely a megadott tartományon belül van egy ReadOnlySpan<T>-ben
type: docs
weight: 196
url: /hu/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) függvény


Megkeresi az első elem indexét, amely a megadott tartományon belül van egy ReadOnlySpan\<T\>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spann elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A span, amelyben keresni kell |
| lowInclusive | const T\& | Az intervallum alsó határa (inkluzív) |
| highInclusive | const T\& | Az intervallum felső határa (inkluzív) |

### Visszatérési érték

A nulla-alapú index az első elemhez, amely az intervallumban van, vagy -1, ha nem található

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) függvény


Megkeresi az első elem indexét, amely a megadott tartományon belül van egy Span\<T\>-ben

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spann elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A span, amelyben keresni kell |
| lowInclusive | const T\& | Az intervallum alsó határa (inkluzív) |
| highInclusive | const T\& | Az intervallum felső határa (inkluzív) |

### Visszatérési érték

A nulla-alapú index az első elemhez, amely az intervallumban van, vagy -1, ha nem található

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)