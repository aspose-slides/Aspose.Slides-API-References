---
title: LastIndexOfImpl()
second_title: Aspose.Slides C++ API-referencia
description: Megkeresi egy érték utolsó indexét egy span-ban.
type: docs
weight: 14
url: /hu/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) függvény


Megkeresi a megadott érték utolsó indexét egy span-ban.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) a kereséshez |
| length | **int32_t** | A keresés tartománya |
| value | const T\& | A megtaláláshoz keresett érték |

### Visszatérési érték

Az érték utolsó indexe, vagy -1, ha nem található

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Névtér [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)