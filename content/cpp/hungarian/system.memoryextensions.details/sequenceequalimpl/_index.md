---
title: SequenceEqualImpl()
second_title: Aspose.Slides C++ API hivatkozása
description: Ellenőrzi, hogy a két span egyenlő-e a megadott pozícióktól kezdve.
type: docs
weight: 27
url: /hu/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) függvény


Ellenőrzi, hogy a két span egyenlő-e a megadott pozícióktól kezdve.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span-ek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Első span |
| start | const **int32_t** | Kezdő index az első span-ben |
| length | **int32_t** | Az összehasonlítandó elemek száma |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Második span |

### Visszatérési érték

true, ha a megadott tartományok egyenlőek, különben false

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Névtér [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)