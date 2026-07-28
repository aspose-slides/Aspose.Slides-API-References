---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API-referencia
description: Két ReadOnlySpans-t lexikografikusan összehasonlít.
type: docs
weight: 313
url: /hu/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Két ReadOnlySpan értékét összehasonlítja lexikografikusan.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Az első span az összehasonlításhoz |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A második span az összehasonlításhoz |

### Visszatérési érték

- 1 ha span < other, 0 ha span == other, 1 ha span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) függvény

Lexikografikusan összehasonlítja a [Span](../../system/span/) és [ReadOnlySpan](../../system/readonlyspan/) értékét.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | A [Span](../../system/span/) az összehasonlításhoz |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A [ReadOnlySpan](../../system/readonlyspan/) az összehasonlításhoz |

### Visszatérési érték

- 1 ha span < other, 0 ha span == other, 1 ha span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) függvény

Lexikografikusan összehasonlítja a [ReadOnlySpan](../../system/readonlyspan/) és [Span](../../system/span/) értékét.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A spannek elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A [ReadOnlySpan](../../system/readonlyspan/) az összehasonlításhoz |
| other | const [Span](../../system/span/)\<T\>\& | A [Span](../../system/span/) az összehasonlításhoz |

### Visszatérési érték

- 1 ha span < other, 0 ha span == other, 1 ha span > other

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions](../)
* Könyvtár [Aspose.Slides](../../)