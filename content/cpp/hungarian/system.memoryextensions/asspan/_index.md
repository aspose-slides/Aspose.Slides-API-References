---
title: AsSpan()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy spant egy tömbből.
type: docs
weight: 1
url: /hu/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) függvény


Létrehoz egy spant a tömbből.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tömb elemeinek típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | A forrás tömb. |
| start | **int32_t** | A tömb kezdő indexe. |
| length | **int32_t** | A span hossza. |

### Visszatérési érték

Span<T>, amely a tömb megadott részét fedi le.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) függvény


Létrehoz egy csak-olvasásra szánt spant egy karakterláncból.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | A forrás karakterlánc. |
| start | **int32_t** | A karakterlánc kezdő indexe. |
| length | **int32_t** | A span hossza. |

### Visszatérési érték

ReadOnlySpan<char16_t>, amely a karakterlánc megadott részét fedi le.

## Lásd még

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)